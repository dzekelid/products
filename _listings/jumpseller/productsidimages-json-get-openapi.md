---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 0
info:
  title: Jumpseller Get Products Images
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
  /products/sku/{sku}.json:
    get:
      summary: Get Products Sku Sku
      description: ""
      operationId: getProductsSkuSku.json
      x-api-path-slug: productsskusku-json-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: sku
        description: SKU of the Product
      responses:
        200:
          description: OK
      tags:
      - Products
      - Sku
      - Sku
      - Json
  /products/status/{status}.json:
    get:
      summary: Get Products Status Status
      description: ""
      operationId: getProductsStatusStatus.json
      x-api-path-slug: productsstatusstatus-json-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: status
        description: Status of the Product used as filter
      responses:
        200:
          description: OK
      tags:
      - Products
      - Status
      - Status
      - Json
  /products/status/{status}/count.json:
    get:
      summary: Get Products Status Status Count
      description: ""
      operationId: getProductsStatusStatusCount.json
      x-api-path-slug: productsstatusstatuscount-json-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: status
        description: Status of the Product used as filter
      responses:
        200:
          description: OK
      tags:
      - Products
      - Status
      - Status
      - Count
      - Json
  /products/{id}.json:
    delete:
      summary: Delete Products
      description: ""
      operationId: deleteProducts.json
      x-api-path-slug: productsid-json-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Json
    get:
      summary: Get Products
      description: ""
      operationId: getProducts.json
      x-api-path-slug: productsid-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Json
    put:
      summary: Put Products
      description: ""
      operationId: putProducts.json
      x-api-path-slug: productsid-json-put
      parameters:
      - in: body
        name: body
        description: Product parameters to change
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Json
  /products/{id}/fields.json:
    get:
      summary: Get Products Fields
      description: ""
      operationId: getProductsFields.json
      x-api-path-slug: productsidfields-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Fields
      - Json
    post:
      summary: Post Products Fields
      description: ""
      operationId: postProductsFields.json
      x-api-path-slug: productsidfields-json-post
      parameters:
      - in: body
        name: body
        description: Product Custom Field parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Fields
      - Json
  /products/{id}/fields/count.json:
    get:
      summary: Get Products Fields Count
      description: ""
      operationId: getProductsFieldsCount.json
      x-api-path-slug: productsidfieldscount-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Fields
      - Count
      - Json
  /products/{id}/images.json:
    get:
      summary: Get Products Images
      description: ""
      operationId: getProductsImages.json
      x-api-path-slug: productsidimages-json-get
      parameters:
      - in: path
        name: id
        description: ID of the Product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
      - Id
      - Images
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