{
  "info": {
    "name": "Sustainable Facilities Tool API Products",
    "_postman_id": "172eb62f-8cf2-4286-a095-14a6325f3f7a",
    "description": "Returns all products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "products",
      "item": [
        {
          "id": "00c73c0e-37da-4330-a32e-8f283e48f806",
          "name": "getProducts",
          "request": {
            "url": "http://api.data.gov/sftool/v1/products",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all products"
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
              "id": "5d74e051-893a-4680-89d8-a7c1ba77b71e"
            }
          ]
        }
      ]
    }
  ]
}