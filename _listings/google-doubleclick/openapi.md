swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
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