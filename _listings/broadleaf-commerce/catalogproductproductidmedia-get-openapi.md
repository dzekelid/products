---
swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 0
info:
  title: Broadleaf Commerce API Get Catalog Product Media
  description: Get catalog product media.
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /related-products:
    get:
      summary: Get Related Products
      description: Get related products.
      operationId: getRelatedProducts
      x-api-path-slug: relatedproducts-get
      parameters:
      - in: query
        name: categoryId
        description: categoryId
      - in: query
        name: categoryKey
        description: categoryKey
      - in: query
        name: includePriceData
        description: includePriceData
      - in: query
        name: includePromotionMessages
        description: includePromotionMessages
      - in: query
        name: productId
        description: productId
      - in: query
        name: productKey
        description: productKey
      - in: query
        name: quantity
        description: quantity
      - in: query
        name: type
        description: type
      responses:
        200:
          description: OK
      tags:
      - Related
      - Products
  /catalog/product/{id}:
    get:
      summary: Get Catalog Product
      description: Get catalog product.
      operationId: getCatalogProduct
      x-api-path-slug: catalogproductid-get
      parameters:
      - in: path
        name: id
        description: id
      - in: query
        name: includePriceData
        description: includePriceData
      - in: query
        name: includePromotionMessages
        description: includePromotionMessages
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
  /catalog/product/{productId}/attributes:
    get:
      summary: Get Catalog Product Attributes
      description: Get catalog product attributes.
      operationId: getCatalogProductProductAttributes
      x-api-path-slug: catalogproductproductidattributes-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Attributes
  /catalog/product/{productId}/categories:
    get:
      summary: Get Catalog Product Categories
      description: Get catalog product categories.
      operationId: getCatalogProductProductCategories
      x-api-path-slug: catalogproductproductidcategories-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Categories
  /catalog/product/{productId}/crosssale:
    get:
      summary: Get Catalog Product Crosssale
      description: Get catalog product crosssale.
      operationId: getCatalogProductProductCrosssale
      x-api-path-slug: catalogproductproductidcrosssale-get
      parameters:
      - in: query
        name: limit
        description: limit
      - in: query
        name: offset
        description: offset
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Crosssale
  /catalog/product/{productId}/defaultSku:
    get:
      summary: Get Catalog Product Default sku
      description: Get catalog product default sku.
      operationId: getCatalogProductProductDefaultsku
      x-api-path-slug: catalogproductproductiddefaultsku-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Default
      - Sku
  /catalog/product/{productId}/media:
    get:
      summary: Get Catalog Product Media
      description: Get catalog product media.
      operationId: getCatalogProductProductMedia
      x-api-path-slug: catalogproductproductidmedia-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Media
  /catalog/product/{productId}/skus:
    get:
      summary: Get Catalog Product Skus
      description: Get catalog product skus.
      operationId: getCatalogProductProductSkus
      x-api-path-slug: catalogproductproductidskus-get
      parameters:
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Skus
  /catalog/product/{productId}/upsale:
    get:
      summary: Get Catalog Product Upsale
      description: Get catalog product upsale.
      operationId: getCatalogProductProductUpsale
      x-api-path-slug: catalogproductproductidupsale-get
      parameters:
      - in: query
        name: limit
        description: limit
      - in: query
        name: offset
        description: offset
      - in: path
        name: productId
        description: productId
      responses:
        200:
          description: OK
      tags:
      - Catalog
      - Product
      - Upsale
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