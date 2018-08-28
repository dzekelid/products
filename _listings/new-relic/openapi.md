swagger: "2.0"
x-collection-name: New Relic
x-complete: 1
info:
  title: New Relic
  version: 1.0.0
basePath: v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /usages/{product}.{format}:
    get:
      summary: Get Usages Product . Format
      description: |-
        Show a list of usage for a product in a given time frame.

        NOTE: Currently you must request 1 month of data, or less, to retrieve daily usage. Requests for greater than 1 month will currently return only monthly usage.
      operationId: getUsagesProduct.Format
      x-api-path-slug: usagesproduct-format-get
      parameters:
      - in: query
        name: end_date
        description: 'Format: YYYY-MM-DD'
        type: date
      - in: query
        name: include_subaccounts
        description: 'Include subaccounts usage? (default: false)'
        type: boolean
      - in: path
        name: product
        description: 'Available: apm, browser, mobile'
        type: string
      - in: query
        name: start_date
        description: 'Format: YYYY-MM-DD'
        type: date
      responses:
        200:
          description: OK
      tags:
      - Usages
      - Product
      - .
      - Format