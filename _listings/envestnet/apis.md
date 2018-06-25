---
name: Envestnet
x-slug: envestnet
description: Build and transform financial apps and services with access to financial
  data through our APIs and digital solutions for banks, developers, and innovators.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1691-yodlee.jpg
x-kinRank: "8"
x-alexaRank: "84912"
tags: Products
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/apis.md
specificationVersion: "0.14"
apis:
- name: Crunch Base Get Products
  x-api-slug: crunch-base
  description: Get Products
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1691-yodlee.jpg
  humanURL: http://www.yodlee.com/
  baseURL: https://api.crunchbase.com//v/3//products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/products-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/products-get-openapi.md
- name: Crunch Base Get Products
  x-api-slug: crunch-base
  description: Get Products Using Permalink
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1691-yodlee.jpg
  humanURL: http://www.yodlee.com/
  baseURL: https://api.crunchbase.com//v/3//products/{permalink}
  tags: Products,Permalink
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/productspermalink-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/productspermalink-get-openapi.md
- name: Crunch Base Get Product Relationships
  x-api-slug: crunch-base
  description: Get Product Relationships
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1691-yodlee.jpg
  humanURL: http://www.yodlee.com/
  baseURL: https://api.crunchbase.com//v/3//products/{permalink}/{relationship_name}
  tags: Products,Permalink,Relationship,Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/productspermalinkrelationship-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/productspermalinkrelationship-name-get-openapi.md
- name: Crunch Base
  x-api-slug: crunch-base
  description: Build and transform financial apps and services with access to financial
    data through our APIs and digital solutions for banks, developers, and innovators.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1691-yodlee.jpg
  humanURL: http://www.yodlee.com/
  baseURL: https://api.crunchbase.com//v/3
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/envestnet/openapi.md
x-common:
- type: x-base
  url: https://rest.developer.yodlee.com/services/srest/
- type: x-blog
  url: http://www.yodlee.com/yodlee-moneycenter-blog/
- type: x-blog-rss
  url: http://www.yodlee.com/yodlee-moneycenter-blog/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/yodlee
- type: x-crunchbase
  url: https://crunchbase.com/organization/yodlee
- type: x-developer
  url: http://developer.yodlee.com/
- type: x-email
  url: Customercare@yodlee.com
- type: x-email
  url: customerservice@yodlee.com
- type: x-github
  url: https://github.com/Yodlee
- type: x-twitter
  url: https://twitter.com/Yodlee
- type: x-website
  url: http://www.yodlee.com/
- type: x-website
  url: http://crunchbase.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---