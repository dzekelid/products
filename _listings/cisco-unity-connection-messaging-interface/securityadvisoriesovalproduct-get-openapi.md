---
swagger: "2.0"
x-collection-name: Cisco Unity Connection Messaging Interface
x-complete: 0
info:
  title: Cisco PSIRT open Vuln Get Security Advisories Oval Product
  description: Used to obtain all the oval advisories that affects the given product
    name.
  contact:
    name: Omar Santos
    email: os@cisco.com
  version: 0.0.3
host: api.cisco.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /security/advisories/cvrf/product:
    get:
      summary: Get Security Advisories Product
      description: Used to obtain all the advisories that affects the given product
        name.
      operationId: used-to-obtain-all-the-advisories-that-affects-the-given-product-name-
      x-api-path-slug: securityadvisoriescvrfproduct-get
      parameters:
      - in: query
        name: product
        description: An product name to obtain security advisories that matches given
          product name
      responses:
        200:
          description: OK
      tags:
      - Security
      - Advisories
      - Product
  /security/advisories/oval/product:
    get:
      summary: Get Security Advisories Oval Product
      description: Used to obtain all the oval advisories that affects the given product
        name.
      operationId: used-to-obtain-all-the-oval-advisories-that-affects-the-given-product-name-
      x-api-path-slug: securityadvisoriesovalproduct-get
      parameters:
      - in: query
        name: product
        description: An product name to obtain security advisories that matches given
          product name
      responses:
        200:
          description: OK
      tags:
      - Security
      - Advisories
      - Oval
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