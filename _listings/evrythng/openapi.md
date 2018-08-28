swagger: "2.0"
x-collection-name: EVRYTHNG
x-complete: 1
info:
  title: EVRYTHNG
  description: the-evrythng-platform-is-a-cloud-platformasaservice-paas-for-storing-sharing-and-analyzing-data-generated-by-physical-objects--the-platform-gives-a-unique-and-permanent-digital-identity-also-known-as-adis-to-each-individual-object-and-allows-authorized-applications-and-users-to-access-it-via-rest-and-pubsub-mqtt-apis--visualisations-in-the-evrythng-dashboard-analytics-conditional-redirections-and-the-reactor-rules-engine-provide-means-to-add-intelligent-behavior-and-features-on-top-of-your-data-to-add-value-
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/{PROD_ID}:
    get:
      summary: /products/{id} (O)
      description: OPERATOR reads a specific product.
      operationId: ProductsByPRODIDGet
      x-api-path-slug: productsprod-id-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: PROD_ID
      responses:
        200:
          description: OK
      tags:
      - Products
      - PROD
      - ID
  /products:
    get:
      summary: /products (A)
      description: APP Reads the list of all products visible.
      operationId: ProductsGet2
      x-api-path-slug: products-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Products
    post:
      summary: /products (O)
      description: OPERATOR creates a product visible in **NO** applications.
      operationId: ProductsPost
      x-api-path-slug: products-post
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
          description: OK
      tags:
      - Products