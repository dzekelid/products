swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /enterprises/{enterpriseId}/products:
    get:
      summary: Get Products
      description: Finds approved products that match a query, or all approved products
        if there is no query.
      operationId: androidenterprise.products.list
      x-api-path-slug: enterprisesenterpriseidproducts-get
      parameters:
      - in: query
        name: approved
        description: Specifies whether to search among all products (false) or among
          only products that have been approved (true)
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: query
        name: language
        description: The BCP47 tag for the users preferred language (e
      - in: query
        name: maxResults
        description: Specifies the maximum number of products that can be returned
          per request
      - in: query
        name: query
        description: The search query as typed in the Google Play store search box
      - in: query
        name: token
        description: A pagination token is contained in a requests response when there
          are more products
      responses:
        200:
          description: OK
      tags:
      - Product
  /enterprises/{enterpriseId}/products/{productId}:
    get:
      summary: Get Product
      description: Retrieves details of a product for display to an enterprise admin.
      operationId: androidenterprise.products.get
      x-api-path-slug: enterprisesenterpriseidproductsproductid-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: query
        name: language
        description: The BCP47 tag for the users preferred language (e
      - in: path
        name: productId
        description: The ID of the product, e
      responses:
        200:
          description: OK
      tags:
      - Product
  /enterprises/{enterpriseId}/products/{productId}/approve:
    post:
      summary: Approve Product
      description: |-
        Approves the specified product and the relevant app permissions, if any. The maximum number of products that you can approve per enterprise customer is 1,000.

        To learn how to use managed Google Play to design and create a store layout to display approved products to your users, see Store Layout Design.
      operationId: androidenterprise.products.approve
      x-api-path-slug: enterprisesenterpriseidproductsproductidapprove-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: productId
        description: The ID of the product
      responses:
        200:
          description: OK
      tags:
      - Product
  /enterprises/{enterpriseId}/products/{productId}/unapprove:
    post:
      summary: Unnarove Product
      description: Unapproves the specified product (and the relevant app permissions,
        if any)
      operationId: androidenterprise.products.unapprove
      x-api-path-slug: enterprisesenterpriseidproductsproductidunapprove-post
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: productId
        description: The ID of the product
      responses:
        200:
          description: OK
      tags:
      - Product
  /enterprises/{enterpriseId}/users/{userId}/availableProductSet:
    get:
      summary: Get Products
      description: Retrieves the set of products a user is entitled to access.
      operationId: androidenterprise.users.getAvailableProductSet
      x-api-path-slug: enterprisesenterpriseidusersuseridavailableproductset-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Product
    put:
      summary: Update Products
      description: Modifies the set of products that a user is entitled to access
        (referred to as whitelisted products). Only products that are approved or
        products that were previously approved (products with revoked approval) can
        be whitelisted.
      operationId: androidenterprise.users.setAvailableProductSet
      x-api-path-slug: enterprisesenterpriseidusersuseridavailableproductset-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: path
        name: userId
        description: The ID of the user
      responses:
        200:
          description: OK
      tags:
      - Product