---
swagger: "2.0"
x-collection-name: Getty Images
x-complete: 0
info:
  title: Getty Images Get Products
  description: "This endpoint returns all products available to the username used
    during authentication. As such, this endpoint requires the use of\r\na fully authorized
    access_token. The product data can then be used as search filters, restricting
    results to images from a specific product.\r\n\r\nYou'll need an API key and access
    token to use this resource. Please see our [Getting Started](http://developers.gettyimages.com/en/getting-started.html)\r\npage
    for more information on how to sign up for an API key."
  version: 1.0.0
host: api.gettyimages.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/products:
    get:
      summary: Get Products
      description: "This endpoint returns all products available to the username used
        during authentication. As such, this endpoint requires the use of\r\na fully
        authorized access_token. The product data can then be used as search filters,
        restricting results to images from a specific product.\r\n\r\nYou'll need
        an API key and access token to use this resource. Please see our [Getting
        Started](http://developers.gettyimages.com/en/getting-started.html)\r\npage
        for more information on how to sign up for an API key."
      operationId: Products_GetProducts
      x-api-path-slug: v3products-get
      parameters:
      - in: header
        name: Accept-Language
        description: Provide a header to specify the language of result values
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: query
        name: fields
        description: Comma separated list of fields
      responses:
        200:
          description: OK
      tags:
      - Images
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