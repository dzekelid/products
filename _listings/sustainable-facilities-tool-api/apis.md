---
name: Sustainable Facilities Tool API
x-slug: sustainable-facilities-tool-api
description: Our core API allows developers to interact with the Sustainable Facilities
  Tool programmatically. Its designed for public use and to be easily integrated into
  other applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Products
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/apis.md
specificationVersion: "0.14"
apis:
- name: Sustainable Facilities Tool API - Products
  x-api-slug: products-get
  description: Returns all products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1/
  tags: Federal Government   GSA, Stack Network, Environment, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/products-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/products-get-openapi.md
- name: Sustainable Facilities Tool API - Product Details
  x-api-slug: productsparameterdetails-get
  description: Returns details for the product selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1/
  tags: Federal Government   GSA, Stack Network, Environment, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/productsparameterdetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/productsparameterdetails-get-openapi.md
- name: Sustainable Facilities Tool API - Related Products
  x-api-slug: servicesparameterrelatedproducts-get
  description: Returns products related to a service by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1/
  tags: Federal Government   GSA, Stack Network, Environment, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/servicesparameterrelatedproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/sustainable-facilities-tool-api/servicesparameterrelatedproducts-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://sugarsync..api.gallery.streamdata.io
- type: x-api-stack
  url: http://sustainable.facilities.tool.api.stack.network
- type: x-developer
  url: https://sftool.gov/developers
- type: x-terms-of-service
  url: https://sftool.gov/developer/terms-of-use
- type: x-twitter
  url: https://twitter.com/sftool
- type: x-website
  url: https://sftool.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---