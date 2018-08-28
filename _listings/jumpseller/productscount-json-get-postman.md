{
  "info": {
    "name": "Jumpseller Get Products Count",
    "_postman_id": "91884a7d-9064-4e5b-b0f6-68142ad5494d",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Countries",
      "item": [
        {
          "id": "33754ddb-d932-4640-a1bb-4db979d17c87",
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
              "id": "5127f17a-78a0-4211-8a85-c1b2547ec832"
            }
          ]
        },
        {
          "id": "d99aee18-00a5-4e1b-bb83-dfc5325105ce",
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
              "id": "4f9eec8d-1772-4860-9d2d-ebf6c9fd0398"
            }
          ]
        },
        {
          "id": "35a26106-be67-4696-9219-e411fbd2e91c",
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
              "id": "92282fbc-adcb-448b-a105-a874e77959f3"
            }
          ]
        },
        {
          "id": "2d3f8d2c-fc09-4d50-abd3-0b5ba0b98a82",
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
              "id": "50b67f34-fed7-4e8c-9a57-fa0d4c260481"
            }
          ]
        }
      ]
    },
    {
      "name": "Products",
      "item": [
        {
          "id": "62be1c47-e4a6-499d-80cd-0f88d0b54dfb",
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
              "id": "4ec71ff7-82c0-4e9b-99f5-101185f71efb"
            }
          ]
        },
        {
          "id": "28e0aa7e-92f3-46a5-8039-f036804c2bea",
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
              "id": "fd3efad3-9fcc-4418-af24-89cc340a5ec8"
            }
          ]
        }
      ]
    }
  ]
}