---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Create a product with predefined ID
  description: Create a product with predefined identifier string
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products:
    get:
      summary: Retrieve a list of products
      description: Retrieve a list of products
      operationId: products.get
      x-api-path-slug: products-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Products
    post:
      summary: Create a Product
      description: Create a Product
      operationId: products.post
      x-api-path-slug: products-post
      parameters:
      - in: body
        name: body
        description: Product resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Product
  /products/{id}:
    delete:
      summary: Delete a product
      description: Delete a product with predefined identifier string
      operationId: products.id.delete
      x-api-path-slug: productsid-delete
      responses:
        200:
          description: OK
      tags:
      - Product
    get:
      summary: Retrieve a product
      description: Retrieve a product with specified identifier string
      operationId: products.id.get
      x-api-path-slug: productsid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Product
    put:
      summary: Create a product with predefined ID
      description: Create a product with predefined identifier string
      operationId: products.id.put
      x-api-path-slug: productsid-put
      parameters:
      - in: body
        name: body
        description: Product resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Product
      - Predefined
      - ID
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