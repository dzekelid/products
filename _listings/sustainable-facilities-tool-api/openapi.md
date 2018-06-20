---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 1
info:
  title: Sustainable Facilities Tool API
  description: our-core-api-allows-developers-to-interact-with-the-sustainable-facilities-tool-programmatically--its-designed-for-public-use-and-to-be-easily-integrated-into-other-applications-
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
---