---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Get Products Search
  description: ""
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products.json:
    get:
      summary: Get Products
      description: ""
      operationId: getProducts.json
      x-api-path-slug: products-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Json
    post:
      summary: Post Products
      description: ""
      operationId: postProducts.json
      x-api-path-slug: products-json-post
      parameters:
      - in: body
        name: body
        description: Product parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Json
  /products/after/{id}.json:
    get:
      summary: Get Products After
      description: ""
      operationId: getProductsAfter.json
      x-api-path-slug: productsafterid-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - After
      - Id
      - Json
  /products/category/{category_id}.json:
    get:
      summary: Get Products Category Category
      description: ""
      operationId: getProductsCategoryCategory.json
      x-api-path-slug: productscategorycategory-id-json-get
      parameters:
      - in: path
        name: category_id
        description: Category ID of the Product used as filter
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Category
      - Category
      - Id
      - Json
  /products/category/{category_id}/count.json:
    get:
      summary: Get Products Category Category Count
      description: ""
      operationId: getProductsCategoryCategoryCount.json
      x-api-path-slug: productscategorycategory-idcount-json-get
      parameters:
      - in: path
        name: category_id
        description: Category ID of the Product used as filter
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Category
      - Category
      - Id
      - Count
      - Json
  /products/count.json:
    get:
      summary: Get Products Count
      description: ""
      operationId: getProductsCount.json
      x-api-path-slug: productscount-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Count
      - Json
  /products/search.json:
    get:
      summary: Get Products Search
      description: ""
      operationId: getProductsSearch.json
      x-api-path-slug: productssearch-json-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: query
        description: Query for the Product
      responses:
        200:
          description: OK
      tags:
      - Products
      - Search
      - Json
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