{
  "info": {
    "name": "Getty Images Search API Get Products",
    "_postman_id": "172de273-113b-4ad1-85e7-5b42d155db54",
    "description": "Get products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Products",
      "item": [
        {
          "id": "6702cde5-9d90-4362-86f7-534a9c7f61f9",
          "name": "getV3Products",
          "request": {
            "url": "http://api.gettyimages.com/v3/products?fields=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept-Language",
                "value": "{}",
                "description": "Specifies the language of result values",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Provide access token in the format of Bearer {token}",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54009b89-ebfc-4e4b-bbfc-73d74ac0bcbd"
            }
          ]
        }
      ]
    }
  ]
}