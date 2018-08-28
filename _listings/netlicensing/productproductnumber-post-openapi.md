---
swagger: "2.0"
x-collection-name: NetLicensing
x-complete: 0
info:
  title: NetLicensing Update product
  description: Sets the provided properties to a product. Return an updated product
  termsOfService: https://www.labs64.com/legal/terms-of-service/netlicensing
  version: 2.x
host: go.netlicensing.io
basePath: /core/v2/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /product:
    get:
      summary: Products list
      description: Return a list of all configured products for the current vendor
      operationId: listProducts
      x-api-path-slug: product-get
      responses:
        200:
          description: OK
      tags:
      - Product
    post:
      summary: Create product
      description: Creates a new product
      operationId: createProduct
      x-api-path-slug: product-post
      parameters:
      - in: formData
        name: active
        description: If set to false, the product is disabled
      - in: formData
        name: description
        description: Product description
      - in: formData
        name: licenseeAutoCreate
        description: If set to true, non-existing licensees will be created at first
          validation attempt
      - in: formData
        name: licenseeSecretMode
        description: Licensee secret mode for product
      - in: formData
        name: licensingInfo
        description: Licensing information
      - in: formData
        name: name
        description: Product name
      - in: formData
        name: number
        description: Unique number that identifies the product
      - in: formData
        name: vatMode
        description: Vat mode for product
      - in: formData
        name: version
        description: Product version
      responses:
        200:
          description: OK
      tags:
      - Product
  /product/{productNumber}:
    delete:
      summary: Delete product
      description: Delete a product by number
      operationId: deleteProduct
      x-api-path-slug: productproductnumber-delete
      parameters:
      - in: query
        name: forceCascade
        description: Force object deletion and all descendants
      - in: path
        name: productNumber
        description: Unique number that identifies the product
      responses:
        200:
          description: OK
      tags:
      - Product
      - ProductNumber
    get:
      summary: Get product
      description: Return a product by productNumber
      operationId: productNumber
      x-api-path-slug: productproductnumber-get
      parameters:
      - in: path
        name: productNumber
        description: Unique number that identifies the product
      responses:
        200:
          description: OK
      tags:
      - Product
      - ProductNumber
    post:
      summary: Update product
      description: Sets the provided properties to a product. Return an updated product
      operationId: updateProduct
      x-api-path-slug: productproductnumber-post
      parameters:
      - in: formData
        name: active
        description: If set to false, the product is disabled
      - in: formData
        name: description
        description: Product description
      - in: formData
        name: licenseeAutoCreate
        description: If set to true, non-existing licensees will be created at first
          validation attempt
      - in: formData
        name: licenseeSecretMode
        description: Licensee secret mode for product
      - in: formData
        name: licensingInfo
        description: Licensing information
      - in: formData
        name: name
        description: Product name
      - in: formData
        name: number
        description: New product number (update)
      - in: path
        name: productNumber
        description: Unique number that identifies the product
      - in: formData
        name: vatMode
        description: Vat mode for product
      - in: formData
        name: version
        description: Product version
      responses:
        200:
          description: OK
      tags:
      - Product
      - ProductNumber
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