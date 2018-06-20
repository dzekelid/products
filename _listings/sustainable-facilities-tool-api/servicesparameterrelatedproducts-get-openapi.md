---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 0
info:
  title: Sustainable Facilities Tool API Related Products
  description: Returns products related to a service by parameter.
  termsOfService: https://sftool.gov/developer/terms-of-use
  version: 1.0.0
host: api.data.gov
basePath: /sftool/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products:
    get:
      summary: Products
      description: Returns all products.
      operationId: getProducts
      x-api-path-slug: products-get
      responses:
        200:
          description: OK
      tags:
      - Products
  /products/{parameter}/details:
    get:
      summary: Product Details
      description: Returns details for the product selected by parameter.
      operationId: getProductDetails
      x-api-path-slug: productsparameterdetails-get
      responses:
        200:
          description: OK
      tags:
      - Products
  /services/{parameter}/related-products:
    get:
      summary: Related Products
      description: Returns products related to a service by parameter.
      operationId: getRelatedProducts
      x-api-path-slug: servicesparameterrelatedproducts-get
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