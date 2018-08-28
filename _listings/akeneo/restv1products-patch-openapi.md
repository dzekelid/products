---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 0
info:
  title: Akeneo PIM API products
  description: Products.
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/products:
    get:
      summary: products
      description: Products.
      operationId: RestV1ProductsGet
      x-api-path-slug: restv1products-get
      parameters:
      - in: header
        name: Content-Type
      - in: header
        name: Cookie
      responses:
        200:
          description: OK
      tags:
      - Products
    patch:
      summary: products
      description: Products.
      operationId: RestV1ProductsPatch
      x-api-path-slug: restv1products-patch
      parameters:
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