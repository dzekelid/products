---
swagger: "2.0"
x-collection-name: New Relic
x-complete: 0
info:
  title: New Relic Get Usages Product . Format
  version: 1.0.0
  description: |-
    Show a list of usage for a product in a given time frame.

    NOTE: Currently you must request 1 month of data, or less, to retrieve daily usage. Requests for greater than 1 month will currently return only monthly usage.
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