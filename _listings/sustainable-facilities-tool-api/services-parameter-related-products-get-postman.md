{
  "info": {
    "name": "Sustainable Facilities Tool API Related Products",
    "_postman_id": "b62a3f83-c377-4e32-9ae3-b9c459bf11d5",
    "description": "Returns products related to a service by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "products",
      "item": [
        {
          "id": "19dfdfb7-36ba-4581-b392-9d34d72e9b89",
          "name": "getRelatedProducts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "services/:parameter/related-products"
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
            "description": "Returns products related to a service by parameter"
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
              "id": "4a59fedb-433e-49ec-87d3-4c6612bc1ec8"
            }
          ]
        }
      ]
    }
  ]
}