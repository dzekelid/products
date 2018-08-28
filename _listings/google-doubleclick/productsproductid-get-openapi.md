---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get Product
  version: 1.0.0
  description: Gets the requested product by id.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/{productId}:
    get:
      summary: Get Product
      description: Gets the requested product by id.
      operationId: adexchangebuyer.products.get
      x-api-path-slug: productsproductid-get
      parameters:
      - in: path
        name: productId
        description: The id for the product to get the head revision for
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Product
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