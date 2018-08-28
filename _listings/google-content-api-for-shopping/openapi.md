swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 1
info:
  title: Content API for Shopping
  description: manages-product-items-inventory-and-merchant-center-accounts-for-google-shopping-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/batch:
    post:
      summary: Product Batches
      description: Retrieves, inserts, and deletes multiple products in a single request.
        This method can only be called for non-multi-client accounts.
      operationId: content.products.custombatch
      x-api-path-slug: productsbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Product
      - Batches
  /productstatuses/batch:
    post:
      summary: Product Batch
      description: Gets the statuses of multiple products in a single request. This
        method can only be called for non-multi-client accounts.
      operationId: content.productstatuses.custombatch
      x-api-path-slug: productstatusesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Product
      - Batch
  /{merchantId}/products:
    post:
      summary: Upload Product
      description: Uploads a product to your Merchant Center account. If an item with
        the same channel, contentLanguage, offerId, and targetCountry already exists,
        this method updates that entry. This method can only be called for non-multi-client
        accounts.
      operationId: content.products.insert
      x-api-path-slug: merchantidproducts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Product
  /{merchantId}/products/{productId}:
    delete:
      summary: Delete Product
      description: Deletes a product from your Merchant Center account. This method
        can only be called for non-multi-client accounts.
      operationId: content.products.delete
      x-api-path-slug: merchantidproductsproductid-delete
      parameters:
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: path
        name: productId
        description: The ID of the product
      responses:
        200:
          description: OK
      tags:
      - Product
    get:
      summary: Get Product
      description: Retrieves a product from your Merchant Center account. This method
        can only be called for non-multi-client accounts.
      operationId: content.products.get
      x-api-path-slug: merchantidproductsproductid-get
      parameters:
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: path
        name: productId
        description: The ID of the product
      responses:
        200:
          description: OK
      tags:
      - Product
  /{merchantId}/productstatuses:
    get:
      summary: Get Product Status
      description: Lists the statuses of the products in your Merchant Center account.
        This method can only be called for non-multi-client accounts.
      operationId: content.productstatuses.list
      x-api-path-slug: merchantidproductstatuses-get
      parameters:
      - in: query
        name: includeInvalidInsertedItems
        description: Flag to include the invalid inserted items in the result of the
          list request
      - in: query
        name: maxResults
        description: The maximum number of product statuses to return in the response,
          used for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Product
      - Status
  /{merchantId}/productstatuses/{productId}:
    get:
      summary: Get Product Status
      description: Gets the status of a product from your Merchant Center account.
        This method can only be called for non-multi-client accounts.
      operationId: content.productstatuses.get
      x-api-path-slug: merchantidproductstatusesproductid-get
      parameters:
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: path
        name: productId
        description: The ID of the product
      responses:
        200:
          description: OK
      tags:
      - Product
      - Status