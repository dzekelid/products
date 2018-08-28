---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 0
info:
  title: Digital River Shopper API Get Shoppers Me Products Point Of Promotions Popid
    Offers
  description: Get shoppers me products point of promotions popid offers.
  version: v1
host: store.digitalriver.com
basePath: /store/{mysite}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/shoppers/me/categories/{id}/products:
    get:
      summary: Get Shoppers Me Categories Products
      description: Get shoppers me categories products.
      operationId: getV1ShoppersMeCategoriesProducts
      x-api-path-slug: v1shoppersmecategoriesidproducts-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Categories
      - Products
  /v1/shoppers/me/products:
    get:
      summary: Get Shoppers Me Products
      description: Get shoppers me products.
      operationId: getV1ShoppersMeProducts
      x-api-path-slug: v1shoppersmeproducts-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
  /v1/shoppers/me/products/{id}:
    get:
      summary: Get Shoppers Me Products
      description: Get shoppers me products.
      operationId: getV1ShoppersMeProducts
      x-api-path-slug: v1shoppersmeproductsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
  /v1/shoppers/me/products/{id}/point-of-promotions/{popId}/offers:
    get:
      summary: Get Shoppers Me Products Point Of Promotions Popid Offers
      description: Get shoppers me products point of promotions popid offers.
      operationId: getV1ShoppersMeProductsPointOfPromotionsPopOffers
      x-api-path-slug: v1shoppersmeproductsidpointofpromotionspopidoffers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: popId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Products
      - Point
      - Promotions
      - Popid
      - Offers
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---