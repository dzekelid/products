swagger: "2.0"
x-collection-name: NetLicensing
x-complete: 1
info:
  title: NetLicensing
  description: the-labs64-netlicensing-restful-api-gives-you-access-to-netlicensings-core-features--you-authenticate-to-the-netlicensing-api-by-providing-your-account-credentials-or-simply-use-our-demo-account--find-out-more-about-labs64-netlicensing-at-netlicensing-io-
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