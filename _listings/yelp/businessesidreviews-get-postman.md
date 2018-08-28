{
  "info": {
    "name": "Yelp Get Businesses Reviews",
    "_postman_id": "15f53382-08b3-485a-a321-69e30a2e47b5",
    "description": "Get businesses reviews.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Businesses",
      "item": [
        {
          "id": "0cd1019b-1ee1-45bf-ba73-c7c00ac48c21",
          "name": "getBusinessesSearch",
          "request": {
            "url": "http://api.yelp.com/v3/businesses/search?No Name=%7B%7D&term=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get businesses search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f13b53db-238f-4c16-b4b6-409b398682e0"
            }
          ]
        },
        {
          "id": "747b1435-2021-43e6-b852-da47fe972b3e",
          "name": "getBusinesses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yelp.com",
              "path": [
                "v3",
                "businesses/:id"
              ],
              "query": [
                {
                  "key": "No Name",
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
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get businesses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ea5c7fd-9df5-484f-a89f-40cab8823648"
            }
          ]
        },
        {
          "id": "a74f9548-80dc-4f57-8ed5-15628ba5d0ef",
          "name": "getBusinessesReviews",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yelp.com",
              "path": [
                "v3",
                "businesses/:id/reviews"
              ],
              "query": [
                {
                  "key": "No Name",
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
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get businesses reviews."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3ac457c-1123-4bbb-820b-63b8e79be7bb"
            }
          ]
        }
      ]
    }
  ]
}