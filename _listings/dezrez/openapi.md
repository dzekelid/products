swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/tenantreferncing/products:
    get:
      summary: Gets the available products for tenant referencing
      description: Gets the available products for tenant referencing.
      operationId: TenantReferencing_GetProducts
      x-api-path-slug: apitenantreferncingproducts-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - Available
      - Productstenant
      - Referencing