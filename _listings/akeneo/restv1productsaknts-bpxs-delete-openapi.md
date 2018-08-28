---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 0
info:
  title: Akeneo PIM API product
  description: Assuming that the given identifier is the identifier of an existing
    product
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
    post:
      summary: product
      description: Assuming that there is no "new_product" already existing
      operationId: RestV1ProductsPost
      x-api-path-slug: restv1products-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-type
      responses:
        200:
          description: OK
      tags:
      - Product
  /rest/v1/published-products:
    get:
      summary: published products (2.x and EE only)
      description: Published products (2.x and ee only).
      operationId: RestV1PublishedProductsGet
      x-api-path-slug: restv1publishedproducts-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Published
      - Products
      - (2
      - X
      - EE
      - Only)
  /rest/v1/products/AKNSTK:
    get:
      summary: product
      description: Assuming that the given identifier is the identifier of an existing
        product
      operationId: RestV1ProductsAKNSTKGet
      x-api-path-slug: restv1productsaknstk-get
      responses:
        200:
          description: OK
      tags:
      - Product
    patch:
      summary: product
      description: Product.
      operationId: RestV1ProductsAKNSTKPatch
      x-api-path-slug: restv1productsaknstk-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-type
      responses:
        200:
          description: OK
      tags:
      - Product
  /rest/v1/products/AKNTS_BPXS:
    delete:
      summary: product
      description: Assuming that the given identifier is the identifier of an existing
        product
      operationId: RestV1ProductsAKNTSBPXSDelete
      x-api-path-slug: restv1productsaknts-bpxs-delete
      parameters:
      - in: header
        name: Content-type
      responses:
        200:
          description: OK
      tags:
      - Product
  /rest/v1/product-models/amor:
    get:
      summary: product model (2.x only)
      description: Assuming that the given code is the code of an existing product
        model
      operationId: RestV1ProductModelsAmorGet
      x-api-path-slug: restv1productmodelsamor-get
      responses:
        200:
          description: OK
      tags:
      - Product
      - Model
      - (2
      - X
      - Only)
    patch:
      summary: product model (2.x only)
      description: Assuming that the given code is the code of an existing product
        model
      operationId: RestV1ProductModelsAmorPatch
      x-api-path-slug: restv1productmodelsamor-patch
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
      - Product
      - Model
      - (2
      - X
      - Only)
  /rest/v1/product-models:
    get:
      summary: product models (2.x only)
      description: Product models (2.x only).
      operationId: RestV1ProductModelsGet
      x-api-path-slug: restv1productmodels-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Product
      - Models
      - (2
      - X
      - Only)
    post:
      summary: product model (2.x only)
      description: Product model (2.x only).
      operationId: RestV1ProductModelsPost
      x-api-path-slug: restv1productmodels-post
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
      - Product
      - Model
      - (2
      - X
      - Only)
    patch:
      summary: product models (2.x only)
      description: Product models (2.x only).
      operationId: RestV1ProductModelsPatch
      x-api-path-slug: restv1productmodels-patch
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
      - Product
      - Models
      - (2
      - X
      - Only)
  /rest/v1/published-products/13527420:
    get:
      summary: published product (2.x and EE only)
      description: Assuming that the given identifier is the identifier of an existing
        product that is currently published
      operationId: RestV1PublishedProducts13527420Get
      x-api-path-slug: restv1publishedproducts13527420-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Published
      - Product
      - (2
      - X
      - EE
      - Only)
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