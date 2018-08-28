---
swagger: "2.0"
x-collection-name: Digital River
x-complete: 0
info:
  title: Digital River Shopper API Get Shoppers Me Product Search
  description: Get shoppers me product search.
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
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}/product-offers:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid Product Offers
      description: Get shoppers me point of promotions offers offerid product offers.
      operationId: getV1ShoppersMePointOfPromotionsOffersOfferProductOffers
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferidproductoffers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
      - Product
      - Offers
  /v1/shoppers/me/point-of-promotions/{id}/offers/{offerId}/product-offers/{productId}:
    get:
      summary: Get Shoppers Me Point Of Promotions Offers Offerid Product Offers Productid
      description: Get shoppers me point of promotions offers offerid product offers
        productid.
      operationId: getV1ShoppersMePointOfPromotionsOffersOfferProductOffersProduct
      x-api-path-slug: v1shoppersmepointofpromotionsidoffersofferidproductoffersproductid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: offerId
      - in: path
        name: productId
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Point
      - Promotions
      - Offers
      - Offerid
      - Product
      - Offers
      - Productid
  /v1/shoppers/me/product-search:
    get:
      summary: Get Shoppers Me Product Search
      description: Get shoppers me product search.
      operationId: getV1ShoppersMeProductSearch
      x-api-path-slug: v1shoppersmeproductsearch-get
      responses:
        200:
          description: OK
      tags:
      - Shoppers
      - Me
      - Product
      - Search
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