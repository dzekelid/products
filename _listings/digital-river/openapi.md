---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 1
info:
  title: Digital River Shopper API
  description: the-dr-connect-shopper-api-operates-on-a-store-and-products-that-are-set-up-in-global-commerce--
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
  /v1/shoppers/me/products/{id}/purchase:
    post:
      summary: Post Shoppers Me Products Purchase
      description: Post shoppers me products purchase.
      operationId: postV1ShoppersMeProductsPurchase
      x-api-path-slug: v1shoppersmeproductsidpurchase-post
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
      - Purchase
  /v1/shoppers/me/products/{id}/variations:
    get:
      summary: Get Shoppers Me Products Variations
      description: Get shoppers me products variations.
      operationId: getV1ShoppersMeProductsVariations
      x-api-path-slug: v1shoppersmeproductsidvariations-get
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
      - Variations
---