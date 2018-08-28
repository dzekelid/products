{
  "info": {
    "name": "Jumpseller Get Products Fields Count",
    "_postman_id": "7617ec8b-d6db-43f8-9e4a-ca706902bb72",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "84076479-fb59-40a8-bd1a-d08f22fe8643",
          "name": "getCountries.json",
          "request": {
            "url": "http://api.jumpseller.com/v1/countries.json?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve all countries.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e589b628-0b2a-48ba-b753-5897061da9dd"
            }
          ]
        },
        {
          "id": "2ef0228d-f89f-4361-91b3-041d8d1fd04a",
          "name": "getCountriesCountryCode.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "countries/:country_code.json"
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
                  "id": "country_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a single country information.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4cbdbd0d-aaef-451b-afe7-622567a1e7d8"
            }
          ]
        },
        {
          "id": "9955ac2d-545c-411a-9b8e-77764def7ebd",
          "name": "getCountriesCountryCodeRegions.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "countries/:country_code/regions.json"
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
                  "id": "country_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve all regions from a single country.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0f1f991-280d-4c50-b358-4c0a6f92497a"
            }
          ]
        },
        {
          "id": "2d1c1938-ebaf-4485-b36d-b9bca257c5f8",
          "name": "getCountriesCountryCodeRegionsRegionCode.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "countries/:country_code/regions/:region_code.json"
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
                  "id": "country_code",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "region_code",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a single region information object.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b12876a1-b5d1-4830-9c61-da96b6ff742f"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "a2a1be25-1f88-48e3-b620-36230f327e48",
          "name": "getProductsCategoryCategoryCount.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "products/category/:category_id/count.json"
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
                  "id": "category_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Products Category Category Count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b3071d7-d66d-4c7c-ae36-31ab7f8cae9e"
            }
          ]
        },
        {
          "id": "c677bce4-ce0e-479a-97a5-14d16e5d7602",
          "name": "getProductsCount.json",
          "request": {
            "url": "http://api.jumpseller.com/v1/products/count.json?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Products Count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51961bd9-ffc9-4e57-9140-3ef95e9bcb13"
            }
          ]
        },
        {
          "id": "2d90dd31-e3c9-493b-9a26-0eed5695bca5",
          "name": "getProductsStatusStatusCount.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "products/status/:status/count.json"
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
                  "id": "status",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Products Status Status Count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "500f6eb6-43b9-49f3-af9e-d29da28e2daf"
            }
          ]
        },
        {
          "id": "c27cec07-75e2-4bc5-a79b-a1594abff502",
          "name": "getProductsFieldsCount.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "products/:id/fields/count.json"
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
            "body": {
              "mode": "raw"
            },
            "description": "Get Products Fields Count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a058124d-e353-49e3-bc8b-58e42cfe455c"
            }
          ]
        }
      ]
    }
  ]
}