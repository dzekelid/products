---
swagger: "2.0"
x-collection-name: EVRYTHNG
x-complete: 0
info:
  title: EVRYTHNG /products (O)
  description: OPERATOR creates a product visible in **NO** applications.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/{PROD_ID}:
    get:
      summary: /products/{id} (O)
      description: OPERATOR reads a specific product.
      operationId: ProductsByPRODIDGet
      x-api-path-slug: productsprod-id-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: PROD_ID
      responses:
        200:
          description: OK
      tags:
      - Products
      - PROD
      - ID
  /products:
    get:
      summary: /products (A)
      description: APP Reads the list of all products visible.
      operationId: ProductsGet2
      x-api-path-slug: products-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Products
    post:
      summary: /products (O)
      description: OPERATOR creates a product visible in **NO** applications.
      operationId: ProductsPost
      x-api-path-slug: products-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Products
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