---
swagger: "2.0"
x-collection-name: Envestnet
x-complete: 1
info:
  title: Crunch Base
  description: the-crunchbase-api-is-a-relatively-straightforward-rest-service-that-allows-developers-to-access-data-in-the-business-graph-
  termsOfService: https://data.crunchbase.com/v3/page/accessing-the-dataset
  contact:
    name: Crunchbase
    url: https://groups.google.com/forum/#!forum/crunchbase-api
    email: data@crunchbase.com
  version: v3
host: api.crunchbase.com
basePath: /v/3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products:
    get:
      summary: Get Products
      description: Get Products
      operationId: products
      x-api-path-slug: products-get
      parameters:
      - in: query
        name: page
        description: the 1-indexed page number to retrieve
      - in: query
        name: sort_order
        description: The sort order for the collection
      - in: query
        name: updated_since
        description: When provided, restricts the result set to Products where updated_at
          >= the passed value
      responses:
        200:
          description: OK
      tags:
      - Products
  /products/{permalink}:
    get:
      summary: Get Products
      description: Get Products Using Permalink
      operationId: products
      x-api-path-slug: productspermalink-get
      parameters:
      - in: path
        name: permalink
        description: The permalink of the organization
      - in: query
        name: user_key
        description: 'Possible values are: 7a582a92032069b4f775a15b1acbe256'
      responses:
        200:
          description: OK
      tags:
      - Products
      - Permalink
  /products/{permalink}/{relationship_name}:
    get:
      summary: Get Product Relationships
      description: Get Product Relationships
      operationId: productRelationships
      x-api-path-slug: productspermalinkrelationship-name-get
      parameters:
      - in: query
        name: page
        description: The page number to retrieve
      - in: path
        name: permalink
        description: The permalink of the Product
      - in: path
        name: relationship_name
        description: The name of the relationship connecting Items
      - in: query
        name: sort_order
        description: The sort order
      responses:
        200:
          description: OK
      tags:
      - Products
      - Permalink
      - Relationship
      - Name
---