{
  "info": {
    "name": "reverb Get Comparison Shopping Pages Reviews",
    "_postman_id": "d9a61910-7066-4211-a290-b9fafdc42bb6",
    "description": "View reviews of a comparison shopping page",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Comparison",
      "item": [
        {
          "id": "6a46ec2f-6a7b-46a4-8054-05d470fae7ad",
          "name": "getComparisonShoppingPages",
          "request": {
            "url": "http://api.reverb.com/api/comparison_shopping_pages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a set of comparison shopping pages based on the current params"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64563ce6-0d72-40e5-94c3-ac0804e68f40"
            }
          ]
        },
        {
          "id": "15ae5a1c-0255-4954-b36e-927881e91e67",
          "name": "getComparisonShoppingPagesFind",
          "request": {
            "url": "http://api.reverb.com/api/comparison_shopping_pages/find?id=%7B%7D&slug=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get comparison shopping pages find."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53c5f858-9c0a-4ed4-afd3-6b337cbdd559"
            }
          ]
        },
        {
          "id": "e23efe48-651e-4766-9b8b-d87f5d8c23a3",
          "name": "getComparisonShoppingPages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "comparison_shopping_pages/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get comparison shopping pages."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a163822d-9edf-4c7e-8940-2e3e941c55d3"
            }
          ]
        },
        {
          "id": "a5784843-8c65-4b27-9176-00376558636a",
          "name": "getComparisonShoppingPagesListings",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "comparison_shopping_pages/:id/listings"
              ],
              "query": [
                {
                  "key": "condition",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "per_page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return new or used listings for a comparison shopping page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11b833b3-e705-4ae3-b1ec-e752966327f0"
            }
          ]
        },
        {
          "id": "e6bf31b5-f4d5-4f12-96cd-84de64e3b418",
          "name": "getComparisonShoppingPagesReviews",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "comparison_shopping_pages/:id/reviews"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "View reviews of a comparison shopping page"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4bc780ee-84a3-4625-933e-eca273e47318"
            }
          ]
        }
      ]
    }
  ]
}