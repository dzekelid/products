---
swagger: "2.0"
x-collection-name: Open Bank Project
x-complete: 0
info:
  title: Open Bank Project Get Account Product
  description: Get Product related to an account
  termsOfService: https://www.openbanking.org.uk/terms
  contact:
    name: Service Desk
    email: ServiceDesk@openbanking.org.uk
  version: 1.0.0
basePath: /open-banking/v2.0
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
      operationId: GetProducts
      x-api-path-slug: products-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Banking
      - Banks
      - Products
  /accounts/{AccountId}/product:
    get:
      summary: Get Account Product
      description: Get Product related to an account
      operationId: GetAccountProduct
      x-api-path-slug: accountsaccountidproduct-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Banking
      - Banks
      - Account
      - Product
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