---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 0
info:
  title: Apigee Edge Get Organizations Name Apiproducts
  description: Lists all API products by name for an organization.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/apiproducts:
    get:
      summary: Get Organizations Name Apiproducts
      description: Lists all API products by name for an organization.
      operationId: getOrganizationsOrgNameApiproducts
      x-api-path-slug: organizationsorg-nameapiproducts-get
      parameters:
      - in: path
        name: org_name
        description: Mention the Organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - API
      - Products
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