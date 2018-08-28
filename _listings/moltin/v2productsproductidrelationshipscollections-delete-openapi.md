---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Delete Products <=> Collections Relationships
  description: Here you can delete a relationship between a `Product` and `Collections`.
    Only relationships to `Collections` specified in the payload will be removed.
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
    put:
      summary: Update a Product Variation
      description: Update a product variation.
      operationId: V2VariationsByVariationIDPut
      x-api-path-slug: v2variationsvariationid-put
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
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variation
    delete:
      summary: Delete a Product Variation
      description: Delete a product variation.
      operationId: V2VariationsByVariationIDDelete
      x-api-path-slug: v2variationsvariationid-delete
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
  /v2/products/{productID}/build:
    post:
      summary: Build Child Products
      description: Build child products.
      operationId: V2ProductsBuildByProductIDPost
      x-api-path-slug: v2productsproductidbuild-post
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
      - Build
      - Child
      - Products
  /v2/products/{productID}/relationships/categories:
    put:
      summary: Update Product <=> Categories Relationships
      description: Here you can update `Categories` to a product. `Categories` specified
        in the payload willbe related to the product any relatiosnhips to `Categories`
        **NOT** specified in payload will be removed.
      operationId: V2ProductsRelationshipsCategoriesByProductIDPut
      x-api-path-slug: v2productsproductidrelationshipscategories-put
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
      - Categories
      - Relationships
    post:
      summary: Create Product <=> Categories Relationships
      description: Here you can add `Categories` to a product. `Categories` specified
        in the payload willbe related to the product.
      operationId: V2ProductsRelationshipsCategoriesByProductIDPost
      x-api-path-slug: v2productsproductidrelationshipscategories-post
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
      - Categories
      - Relationships
    delete:
      summary: Delete Product <=> Categories Relationships
      description: Here you can delete a relationship between a `Product` and `Category`.
        Only relationships to `Categories` specified in the payload will be removed.
      operationId: V2ProductsRelationshipsCategoriesByProductIDDelete
      x-api-path-slug: v2productsproductidrelationshipscategories-delete
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
      - Categories
      - Relationships
  /v2/variations:
    get:
      summary: Get Product Variations List
      description: Get product variations list.
      operationId: V2VariationsGet
      x-api-path-slug: v2variations-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variations
      - List
    post:
      summary: Create a Product Variation
      description: Create a product variation.
      operationId: V2VariationsPost
      x-api-path-slug: v2variations-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variation
  /v2/variations/{variationID}/options/{optionID}:
    put:
      summary: Update a Product Variation Option
      description: Update a product variation option.
      operationId: V2VariationsOptionsByVariationIDAndOptionIDPut
      x-api-path-slug: v2variationsvariationidoptionsoptionid-put
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
        name: optionID
      - in: path
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variation
      - Option
    delete:
      summary: Delete a Product Variation Option
      description: Delete a product variation option.
      operationId: V2VariationsOptionsByVariationIDAndOptionIDDelete
      x-api-path-slug: v2variationsvariationidoptionsoptionid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: optionID
      - in: path
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variation
      - Option
  /v2/variations/{variationID}/options/{optionID}/modifiers/{modifierID}:
    put:
      summary: Update Product Modifier
      description: Update product modifier.
      operationId: V2VariationsOptionsModifiersModifierIDByVariationIDAndOptionIDPut
      x-api-path-slug: v2variationsvariationidoptionsoptionidmodifiersmodifierid-put
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
        name: modifierID
      - in: path
        name: optionID
      - in: path
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Modifier
    delete:
      summary: Delete Product Modifier
      description: Delete product modifier.
      operationId: V2VariationsOptionsModifiersModifierIDByVariationIDAndOptionIDDelete
      x-api-path-slug: v2variationsvariationidoptionsoptionidmodifiersmodifierid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: modifierID
      - in: path
        name: optionID
      - in: path
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Modifier
  /v2/variations/{variationID}/options/{optionID}/modifiers:
    post:
      summary: Create Product Modifier
      description: Create product modifier.
      operationId: V2VariationsOptionsModifiersByVariationIDAndOptionIDPost
      x-api-path-slug: v2variationsvariationidoptionsoptionidmodifiers-post
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
        name: optionID
      - in: path
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Modifier
  /v2/inventories/{productID}:
    get:
      summary: Get stock for a product
      description: Get stock for a product.
      operationId: V2InventoriesByProductIDGet
      x-api-path-slug: v2inventoriesproductid-get
      parameters:
      - in: path
        name: productID
      responses:
        200:
          description: Successful response
      tags:
      - Stocka
      - Products
  /v2/products/attributes:
    get:
      summary: Get Product Attributes
      description: Get product attributes.
      operationId: V2ProductsAttributesGet
      x-api-path-slug: v2productsattributes-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Attributes
  /v2/products:
    post:
      summary: Create a new Product
      description: Create a new product.
      operationId: V2ProductsPost
      x-api-path-slug: v2products-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - New
      - Products
    get:
      summary: Get Products List
      description: Get products list.
      operationId: V2ProductsGet
      x-api-path-slug: v2products-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: query
        name: filter
      - in: query
        name: include
      - in: query
        name: page[limit]
      - in: query
        name: page[offset]
      - in: query
        name: sort
      responses:
        200:
          description: Successful response
      tags:
      - Productss
      - List
  /v2/variations/{variationID}/options:
    post:
      summary: Create a Product Variation Option
      description: Create a product variation option.
      operationId: V2VariationsOptionsByVariationIDPost
      x-api-path-slug: v2variationsvariationidoptions-post
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
        name: variationID
      responses:
        200:
          description: Successful response
      tags:
      - Products
      - Variation
      - Option
  /v2/products/{productID}/relationships/files:
    put:
      summary: Update Products <=> Files Relationships
      description: '`File`''s specified in the payload willbe related to the product
        any relatiosnhips to `File`''s **NOT** specified in payload will be removed.'
      operationId: V2ProductsRelationshipsFilesByProductIDPut
      x-api-path-slug: v2productsproductidrelationshipsfiles-put
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
      - Productss
      - Files
      - Relationships
    post:
      summary: Create Products <=> Files Relationships
      description: Here you can add `File`'s to a product. `File`'s specified in the
        payload willbe related to the product.
      operationId: V2ProductsRelationshipsFilesByProductIDPost
      x-api-path-slug: v2productsproductidrelationshipsfiles-post
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
      - Productss
      - Files
      - Relationships
    delete:
      summary: Delete Products <=> Files Relationship
      description: Here you can delete a relationship between a `Product` and `File`'s.
        Only relationships to `File`'s specified in the payload will be removed.
      operationId: V2ProductsRelationshipsFilesByProductIDDelete
      x-api-path-slug: v2productsproductidrelationshipsfiles-delete
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
      - Productss
      - Files
      - Relationship
  /v2/products/{ProductID}relationships/brands:
    post:
      summary: Create Products <=> Main Image Relationships
      description: |-
        Here you can add a `Main Image` to a product. The `Main Image` will be a file and that file will be shown as the first image for the product it is related to.

        It's worth noting that you can only have 1 main image so unlike other relationships, you will be passing an object instead of an array in the body.

        In the Object, the type will be `main_image` and the ID will be the ID of the file you wish to make the main image for that product.
      operationId: V2ProductsRelationshipsBrandsByProductIDPost2
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
        name: ProductID
      responses:
        200:
          description: Successful response
      tags:
      - Productss
      - Main
      - Image
      - Relationships
    delete:
      summary: Delete Products <=> Main Image Relationships
      description: |-
        Here you can delete the `Main Image` from a product.

        In the Object payload, the type will be `main_image` and the ID will be the ID of the main image you wish to delete from that product.
      operationId: V2ProductsRelationshipsBrandsByProductIDDelete
      x-api-path-slug: v2productsproductidrelationshipsbrands-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: ProductID
      responses:
        200:
          description: Successful response
      tags:
      - Productss
      - Main
      - Image
      - Relationships
  /v2/products/{productID}/relationships/collections:
    put:
      summary: Update Products <=> Collections Relationships
      description: '`Collection`''s specified in the payload willbe related to the
        product any relatiosnhips to `Collection`''s **NOT** specified in payload
        will be removed.'
      operationId: V2ProductsRelationshipsCollectionsByProductIDPut
      x-api-path-slug: v2productsproductidrelationshipscollections-put
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
      - Productss
      - Collections
      - Relationships
    post:
      summary: Create Products <=> Collections Relationships
      description: Here you can add `Collection`'s to a product. `Collection`'s specified
        in the payload willbe related to the product.
      operationId: V2ProductsRelationshipsCollectionsByProductIDPost
      x-api-path-slug: v2productsproductidrelationshipscollections-post
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
      - Productss
      - Collections
      - Relationships
    delete:
      summary: Delete Products <=> Collections Relationships
      description: Here you can delete a relationship between a `Product` and `Collections`.
        Only relationships to `Collections` specified in the payload will be removed.
      operationId: V2ProductsRelationshipsCollectionsByProductIDDelete
      x-api-path-slug: v2productsproductidrelationshipscollections-delete
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
      - Productss
      - Collections
      - Relationships
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