swagger: "2.0"
x-collection-name: Getty Images
x-complete: 1
info:
  title: Getty Images
  description: build-applications-using-the-worlds-most-powerful-imagery
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