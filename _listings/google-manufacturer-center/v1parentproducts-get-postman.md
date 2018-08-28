{
  "info": {
    "name": "Google Manufacturer Center API Get Products",
    "_postman_id": "64879fdf-467c-4a76-9b3d-3419c9fc81f3",
    "description": "Lists all the products in a Manufacturer Center account.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Product",
      "item": [
        {
          "id": "e09c3044-be57-46ad-ab33-89ab0c64717f",
          "name": "manufacturers.accounts.products.list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "manufacturers.googleapis.com",
              "path": [
                "v1/:parent/products"
              ],
              "query": [
                {
                  "key": "pageSize",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "pageToken",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "parent",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all the products in a Manufacturer Center account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99677caa-4107-4159-92a0-9896b17f98fe"
            }
          ]
        }
      ]
    }
  ]
}