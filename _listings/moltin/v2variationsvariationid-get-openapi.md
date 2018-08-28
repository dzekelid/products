---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Get a Product Variation
  description: Get a product variation.
  version: 1.0.0
host: api.moltin.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/products/{productID}/relationships/variations:
    put:
      summary: Update Product <=> Variations Relationships
      description: '`Product Variation`''s specified in the payload willbe related
        to the `Product` any relatiosnhips to `Product Variation`''s **NOT** specified
        in payload will be removed.'
      operationId: V2ProductsRelationshipsVariationsByProductIDPut
      x-api-path-slug: v2productsproductidrelationshipsvariations-put
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variations
      - Relationships
    post:
      summary: Create Product <=> Variations Relationships
      description: Here you can add and remove `Product Variation`'s to a product.
        `Product Variation`'s specified in the payload willbe related to the product.
      operationId: V2ProductsRelationshipsVariationsByProductIDPost
      x-api-path-slug: v2productsproductidrelationshipsvariations-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variations
      - Relationships
    delete:
      summary: Delete Product <=> Variations Relationships
      description: Here you can add and remove `Product Variation`'s to a product.
        Only relationships to `Product Variation`'s specified in the payload will
        be removed.
      operationId: V2ProductsRelationshipsVariationsByProductIDDelete
      x-api-path-slug: v2productsproductidrelationshipsvariations-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variations
      - Relationships
  /v2/inventories/{productID}/transactions:
    get:
      summary: Stock transactions for a product
      description: Stock transactions for a product.
      operationId: V2InventoriesTransactionsByProductIDGet
      x-api-path-slug: v2inventoriesproductidtransactions-get
      parameters:
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Stock
      - Transactionsa
      - Products
    post:
      summary: Create a stock transaction for a product
      description: Create a stock transaction for a product.
      operationId: V2InventoriesTransactionsByProductIDPost
      x-api-path-slug: v2inventoriesproductidtransactions-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Stock
      - Transactiona
      - Products
  /v2/products/{productID}:
    get:
      summary: Get a Product
      description: Get a product.
      operationId: V2ProductsByProductIDGet
      x-api-path-slug: v2productsproductid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
    put:
      summary: Update a Product
      description: Update a product.
      operationId: V2ProductsByProductIDPut
      x-api-path-slug: v2productsproductid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
    delete:
      summary: Delete a Product
      description: Delete a product.
      operationId: V2ProductsByProductIDDelete
      x-api-path-slug: v2productsproductid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
  /v2/products/{productID}/relationships/brands:
    put:
      summary: Update Product <=> Brands Relationships
      description: Here you can set relations `Brand`'s to a product. The result of
        this request will set relationships between product and the specified brnads
        in teh payload and remove any other relations the product had with brands.
      operationId: V2ProductsRelationshipsBrandsByProductIDPut
      x-api-path-slug: v2productsproductidrelationshipsbrands-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Brandss
      - Relationships
    post:
      summary: Create Product <=> Brands Relationships
      description: Here you can add `Brand`'s to a product. The `Brand`'s found in
        the payload will be added to any other relationships to `Brand`'s present.
      operationId: V2ProductsRelationshipsBrandsByProductIDPost
      x-api-path-slug: v2productsproductidrelationshipsbrands-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Brandss
      - Relationships
    delete:
      summary: Delete Products <=> Brands Relationships
      description: Here you can delete a relationship between a `Product` and `Brand`'s.
        Only those relationshops to `Brand`'s specified in the paylaod will be removed.
      operationId: V2ProductsRelationshipsBrandsByProductIDDelete2
      x-api-path-slug: v2productsproductidrelationshipsbrands-delete
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Brands
      - Relationships
  /v2/variations/{variationID}:
    get:
      summary: Get a Product Variation
      description: Get a product variation.
      operationId: V2VariationsByVariationIDGet
      x-api-path-slug: v2variationsvariationid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variation
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