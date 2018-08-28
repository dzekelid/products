---
swagger: "2.0"
x-collection-name: BigCommerce
x-complete: 0
info:
  title: BigCommerce Create a product modifier
  description: ""
  version: 1.0.0
host: api.bigcommerce.com
basePath: /stores
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{store-hash}/v3/catalog/products:
    get:
      summary: Retrieve all products with expanded sub-resources
      description: Shows full product data with a single GET request
      operationId: V3CatalogProductsByStoreHashGet
      x-api-path-slug: storehashv3catalogproducts-get
      parameters:
      - in: query
        name: include
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - ""
      - Products
      - Expanded
      - Sub-resources
    delete:
      summary: Delete multiple products
      description: Deletes products that aren't marked as visible using a filter parameter
      operationId: V3CatalogProductsByStoreHashDelete
      x-api-path-slug: storehashv3catalogproducts-delete
      parameters:
      - in: query
        name: is_visible
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Multiple
      - Products
    post:
      summary: Create a new product with variants
      description: Sample request for creating a new product with variants through
        V3 Catalog API
      operationId: V3CatalogProductsByStoreHashPost
      x-api-path-slug: storehashv3catalogproducts-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Product
      - Variants
  /{store_hash}/v3/catalog/products/{id}/modifiers/{id}:
    delete:
      summary: Delete a product's modifier
      description: ""
      operationId: V3CatalogProductsModifiersIdByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogproductsidmodifiersid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Products
      - Modifier
    get:
      summary: Retrieve a product modifier
      description: ""
      operationId: V3CatalogProductsModifiersIdByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidmodifiersid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Product
      - Modifier
    put:
      summary: Update a product modifier
      description: ""
      operationId: V3CatalogProductsModifiersIdByStoreHashAndIdPut
      x-api-path-slug: store-hashv3catalogproductsidmodifiersid-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Modifier
  /{store-hash}/v3/catalog/products/{id}/images:
    get:
      summary: Retrieve images for a single product
      description: GET request for retrieving images associated with a product
      operationId: V3CatalogProductsImagesByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimages-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Imagesa
      - Single
      - Product
    post:
      summary: Upload a new product image to a single product
      description: Adds a new product image from a publicly accessible URL. May fail
        if the hosting website is forcing HTTPS connections with TLS 1.0 (as this
        has been deprecated).
      operationId: V3CatalogProductsImagesByStoreHashAndIdPost
      x-api-path-slug: storehashv3catalogproductsidimages-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Upload
      - New
      - Product
      - Image
      - To
      - Single
      - Product
  /{store-hash}/v3/catalog/products/{id}:
    get:
      summary: Retrieve a single product with expanded sub-resources
      description: Request a single product with expanded variant information
      operationId: V3CatalogProductsByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsid-get
      parameters:
      - in: path
        name: id
      - in: query
        name: include
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Product
      - Expanded
      - Sub-resources
    put:
      summary: Update a product in the catalog
      description: Updates a single product's information in the catalog
      operationId: V3CatalogProductsByStoreHashAndIdPut
      x-api-path-slug: storehashv3catalogproductsid-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - In
      - Catalog
    delete:
      summary: Delete a single product by ID
      description: Deleting a single product from the catalog by product ID
      operationId: V3CatalogProductsByStoreHashAndIdDelete
      x-api-path-slug: storehashv3catalogproductsid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - By
      - ID
  /{store_hash}/v3/catalog/products/{id}/videos/{id}:
    get:
      summary: Retrieve a video on a product
      description: ""
      operationId: V3CatalogProductsVideosIdByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidvideosid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Video
      - "On"
      - Product
    put:
      summary: Updates an video on a product
      description: ""
      operationId: V3CatalogProductsVideosIdByStoreHashAndIdPut
      x-api-path-slug: store-hashv3catalogproductsidvideosid-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - S
      - Video
      - "On"
      - Product
    delete:
      summary: Delete a video on a product
      description: ""
      operationId: V3CatalogProductsVideosIdByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogproductsidvideosid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Video
      - "On"
      - Product
  /{store_hash}/v3/catalog/products/{id}/videos:
    get:
      summary: Retrieve all videos for a single product
      description: ""
      operationId: V3CatalogProductsVideosByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidvideos-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - ""
      - Videosa
      - Single
      - Product
    post:
      summary: Add a video to a product using a video ID from Youtube
      description: Creates an video on a product using a video ID from Youtube
      operationId: V3CatalogProductsVideosByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogproductsidvideos-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Video
      - To
      - Product
      - Using
      - Video
      - ID
      - From
      - Youtube
  /{store_hash}/v3/catalog/products/{id}/options:
    get:
      summary: Retrieve an array of product options
      description: ""
      operationId: V3CatalogProductsOptionsByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidoptions-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Array
      - Of
      - Product
      - Options
    post:
      summary: Create a product option
      description: ""
      operationId: V3CatalogProductsOptionsByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogproductsidoptions-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Option
  /{store_hash}/v3/catalog/products/{id}/modifiers:
    get:
      summary: Retrieve an array of product modifiers
      description: ""
      operationId: V3CatalogProductsModifiersByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidmodifiers-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Array
      - Of
      - Product
      - Modifiers
    post:
      summary: Create a product modifier
      description: ""
      operationId: V3CatalogProductsModifiersByStoreHashAndIdPost
      x-api-path-slug: store-hashv3catalogproductsidmodifiers-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Modifier
  /{store-hash}/v3/catalog/products/{id}/images/{id}:
    get:
      summary: Retrieve a single product image's data
      description: GET request for a specific product image by ID
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdGet
      x-api-path-slug: storehashv3catalogproductsidimagesid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Single
      - Product
      - Images
      - Data
    put:
      summary: Update product image information
      description: This is used to update the information for an existing product
        image
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdPut
      x-api-path-slug: storehashv3catalogproductsidimagesid-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Image
      - Information
    delete:
      summary: Delete a single product image
      description: Delete a product image and it's description
      operationId: V3CatalogProductsImagesIdByStoreHashAndIdDelete
      x-api-path-slug: storehashv3catalogproductsidimagesid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Product
      - Image
  /{store_id}/v3/catalog/products/{id}/options/{id}:
    put:
      summary: Update a product option
      description: ""
      operationId: V3CatalogProductsOptionsIdByStoreIdAndIdPut
      x-api-path-slug: store-idv3catalogproductsidoptionsid-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: id
      - in: path
        name: store_id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Option
  /{store_hash}/v3/catalog/products/{id}/options/{id}:
    get:
      summary: Retrieve a product option
      description: Gets `Option` object by product id and option id.
      operationId: V3CatalogProductsOptionsIdByStoreHashAndIdGet
      x-api-path-slug: store-hashv3catalogproductsidoptionsid-get
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - Product
      - Option
    delete:
      summary: Delete a product option
      description: ""
      operationId: V3CatalogProductsOptionsIdByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogproductsidoptionsid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Product
      - Option
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