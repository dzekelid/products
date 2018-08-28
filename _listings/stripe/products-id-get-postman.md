{
  "info": {
    "name": "Stripe Get Products",
    "_postman_id": "8e79e882-b7fb-4741-97ef-61d5533b5299",
    "description": "Retrieves the details of an existing product. Supply the unique product ID from either a product creation request or the product list, and Stripe will return the corresponding product information.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "products",
      "item": [
        {
          "id": "95991cea-f470-4679-b496-747c9d511988",
          "name": "getProducts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "products/:id"
              ],
              "query": [
                {
                  "key": "expand",
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
            "description": "Retrieves the details of an existing product"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c321c982-adeb-45b0-9aac-d1c55c076a3a"
            }
          ]
        }
      ]
    }
  ]
}