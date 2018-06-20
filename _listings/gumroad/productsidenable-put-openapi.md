---
swagger: "2.0"
x-collection-name: Gumroad
x-complete: 0
info:
  title: Gumroad Put Products Enable
  description: Enable an existing product.
  termsOfService: https://gumroad.com/terms
  version: v1
host: api.gumroad.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products:
    get:
      summary: Get Products
      description: Retrieve all of the existing products for the authenticated user.
      operationId: getProducts
      x-api-path-slug: products-get
      responses:
        200:
          description: OK
      tags:
      - Products
    post:
      summary: Post Products
      description: Create a new product for the user.
      operationId: postProducts
      x-api-path-slug: products-post
      parameters:
      - in: query
        name: country_available
      - in: query
        name: customizable_price
      - in: query
        name: custom_filetype
      - in: query
        name: custom_permalink
      - in: query
        name: custom_product_type
      - in: query
        name: custom_receipt
      - in: query
        name: custom_summary
      - in: query
        name: description
      - in: query
        name: max_purchase_count
      - in: query
        name: name
      - in: query
        name: preview_urlnornpreview
      - in: query
        name: price
      - in: query
        name: require_shipping
      - in: query
        name: shown_on_profile
      - in: query
        name: urlnornfile
      - in: query
        name: webhook
      responses:
        200:
          description: OK
      tags:
      - Products
  /products/:id:
    delete:
      summary: Delete Products
      description: Permanently delete a product.
      operationId: deleteProducts
      x-api-path-slug: productsid-delete
      responses:
        200:
          description: OK
      tags:
      - Products
    get:
      summary: Get Products
      description: Retrieve the details of a product.
      operationId: getProducts
      x-api-path-slug: productsid-get
      responses:
        200:
          description: OK
      tags:
      - Products
    put:
      summary: Put Products
      description: Edit an existing product.
      operationId: putProducts
      x-api-path-slug: productsid-put
      parameters:
      - in: query
        name: countries_available
      - in: query
        name: customizable_price
      - in: query
        name: custom_filetype
      - in: query
        name: custom_permalink
      - in: query
        name: custom_product_type
      - in: query
        name: custom_receipt
      - in: query
        name: custom_summary
      - in: query
        name: description
      - in: query
        name: max_purchase_count
      - in: query
        name: name
      - in: query
        name: preview_urlnornpreview
      - in: query
        name: price
      - in: query
        name: product
      - in: query
        name: require_shipping
      - in: query
        name: shown_on_profile
      - in: query
        name: subscription_duration
      - in: query
        name: urlnornfile
      - in: query
        name: webhook
      responses:
        200:
          description: OK
      tags:
      - Products
  /products/:id/enable:
    put:
      summary: Put Products Enable
      description: Enable an existing product.
      operationId: putProductsEnable
      x-api-path-slug: productsidenable-put
      responses:
        200:
          description: OK
      tags:
      - Products
      - Enable
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