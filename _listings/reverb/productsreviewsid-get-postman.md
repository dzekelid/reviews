{
  "info": {
    "name": "reverb Get Products Reviews",
    "_postman_id": "bb131a98-1b3c-4795-bcab-d952289075a5",
    "description": "Get products reviews.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Products",
      "item": [
        {
          "id": "482517e2-17d2-4cc9-bea4-e764defeb6fa",
          "name": "getProductsReviews",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "products/reviews/:id"
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
            "description": "Get products reviews."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59adf445-b00f-4770-a1f8-3bd9baf6b944"
            }
          ]
        }
      ]
    }
  ]
}