---
name: Jumpseller
x-slug: jumpseller
description: We founded Jumpseller.com in 2009 in Europe  we called it Vendder back
  then  and released our first version of the Jumpseller product in September 2010.
  After releasing the product we quickly grew to thousands of customers. In November
  2010, we recei...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
x-kinRank: "7"
x-alexaRank: "153745"
tags: Products
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/apis.md
specificationVersion: "0.14"
apis:
- name: Jumpseller Get Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products.json
  tags: Products,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/products-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/products-json-get-openapi.md
- name: Jumpseller Post Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products.json
  tags: Products,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/products-json-post-openapi.md
- name: Jumpseller Get Products After
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/after/{id}.json
  tags: Products,After,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsafterid-json-get-openapi.md
- name: Jumpseller Get Products Category Category
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/category/{category_id}.json
  tags: Products,Category,Category,Id,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productscategorycategory-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productscategorycategory-id-json-get-openapi.md
- name: Jumpseller Get Products Category Category Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/category/{category_id}/count.json
  tags: Products,Category,Category,Id,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productscategorycategory-idcount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productscategorycategory-idcount-json-get-openapi.md
- name: Jumpseller Get Products Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/count.json
  tags: Products,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productscount-json-get-openapi.md
- name: Jumpseller Get Products Search
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/search.json
  tags: Products,Search,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productssearch-json-get-openapi.md
- name: Jumpseller Get Products Sku Sku
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/sku/{sku}.json
  tags: Products,Sku,Sku,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsskusku-json-get-openapi.md
- name: Jumpseller Get Products Status Status
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/status/{status}.json
  tags: Products,Status,Status,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsstatusstatus-json-get-openapi.md
- name: Jumpseller Get Products Status Status Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/status/{status}/count.json
  tags: Products,Status,Status,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsstatusstatuscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsstatusstatuscount-json-get-openapi.md
- name: Jumpseller Delete Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}.json
  tags: Products,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsid-json-delete-openapi.md
- name: Jumpseller Get Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}.json
  tags: Products,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsid-json-get-openapi.md
- name: Jumpseller Put Products
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}.json
  tags: Products,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsid-json-put-openapi.md
- name: Jumpseller Get Products Fields
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields.json
  tags: Products,Id,Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidfields-json-get-openapi.md
- name: Jumpseller Post Products Fields
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields.json
  tags: Products,Id,Fields,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidfields-json-post-openapi.md
- name: Jumpseller Get Products Fields Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields/count.json
  tags: Products,Id,Fields,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidfieldscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidfieldscount-json-get-openapi.md
- name: Jumpseller Get Products Images
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images.json
  tags: Products,Id,Images,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimages-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimages-json-get-openapi.md
- name: Jumpseller Post Products Images
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images.json
  tags: Products,Id,Images,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimages-json-post-openapi.md
- name: Jumpseller Get Products Images Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/count.json
  tags: Products,Id,Images,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimagescount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimagescount-json-get-openapi.md
- name: Jumpseller Delete Products Images Image
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/{image_id}.json
  tags: Products,Id,Images,Image,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimagesimage-id-json-delete-openapi.md
- name: Jumpseller Get Products Images Image
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/{image_id}.json
  tags: Products,Id,Images,Image,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidimagesimage-id-json-get-openapi.md
- name: Jumpseller Get Products Options
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options.json
  tags: Products,Id,Options,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptions-json-get-openapi.md
- name: Jumpseller Post Products Options
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options.json
  tags: Products,Id,Options,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptions-json-post-openapi.md
- name: Jumpseller Get Products Options Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/count.json
  tags: Products,Id,Options,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionscount-json-get-openapi.md
- name: Jumpseller Delete Products Options Option
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}.json
  tags: Products,Id,Options,Option,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-id-json-delete-openapi.md
- name: Jumpseller Get Products Options Option
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}.json
  tags: Products,Id,Options,Option,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-id-json-get-openapi.md
- name: Jumpseller Put Products Options Option
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}.json
  tags: Products,Id,Options,Option,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-id-json-put-openapi.md
- name: Jumpseller Get Products Options Option Values
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values.json
  tags: Products,Id,Options,Option,Id,Values,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvalues-json-get-openapi.md
- name: Jumpseller Post Products Options Option Values
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values.json
  tags: Products,Id,Options,Option,Id,Values,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvalues-json-post-openapi.md
- name: Jumpseller Get Products Options Option Values Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/count.json
  tags: Products,Id,Options,Option,Id,Values,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvaluescount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvaluescount-json-get-openapi.md
- name: Jumpseller Delete Products Options Option Values Value
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/{value_id}.json
  tags: Products,Id,Options,Option,Id,Values,Value,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvaluesvalue-id-json-delete-openapi.md
- name: Jumpseller Get Products Options Option Values Value
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/{value_id}.json
  tags: Products,Id,Options,Option,Id,Values,Value,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvaluesvalue-id-json-get-openapi.md
- name: Jumpseller Put Products Options Option Values Value
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/{value_id}.json
  tags: Products,Id,Options,Option,Id,Values,Value,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidoptionsoption-idvaluesvalue-id-json-put-openapi.md
- name: Jumpseller Get Products Variants
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants.json
  tags: Products,Id,Variants,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidvariants-json-get-openapi.md
- name: Jumpseller Post Products Variants
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants.json
  tags: Products,Id,Variants,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidvariants-json-post-openapi.md
- name: Jumpseller Get Products Variants Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/count.json
  tags: Products,Id,Variants,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidvariantscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidvariantscount-json-get-openapi.md
- name: Jumpseller Get Products Variants Variant
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/{variant_id}.json
  tags: Products,Id,Variants,Variant,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidvariantsvariant-id-json-get-openapi.md
- name: Jumpseller Put Products Variants Variant
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/{variant_id}.json
  tags: Products,Id,Variants,Variant,Id,Json
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/productsidvariantsvariant-id-json-put-openapi.md
- name: Jumpseller
  x-api-slug: jumpseller
  description: We founded Jumpseller.com in 2009 in Europe  we called it Vendder back
    then  and released our first version of the Jumpseller product in September 2010.
    After releasing the product we quickly grew to thousands of customers. In November
    2010, we recei...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/jumpseller/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/vendder
- type: x-email
  url: info@jumpseller.com
- type: x-email
  url: support@jumpseller.com
- type: x-twitter
  url: https://twitter.com/Jumpseller
- type: x-website
  url: http://jumpseller.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---