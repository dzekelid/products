{
  "info": {
    "name": "Sustainable Facilities Tool API Product Details",
    "_postman_id": "b4f0e6ad-746e-43dd-a677-39bdfe8e4bbe",
    "description": "Returns details for the product selected by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "products",
      "item": [
        {
          "id": "ccf2e721-9346-4d0a-b440-f43e32d79c39",
          "name": "getProductDetails",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "products/:parameter/details"
              ],
              "variable": [
                {
                  "id": "parameter",
                  "value": "parameter",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns details for the product selected by parameter"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"id\": \"id\",\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "b7e0aced-288c-4334-824f-d65646a0d133"
            }
          ]
        }
      ]
    }
  ]
}