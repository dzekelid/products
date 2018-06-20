---
name: Gumroad
x-slug: gumroad
description: Sell music, comics, software, books, and films directly to your audience.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
x-kinRank: "8"
x-alexaRank: "4658"
tags: Products
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/apis.md
specificationVersion: "0.14"
apis:
- name: Gumroad Get Products
  x-api-slug: gumroad
  description: Retrieve all of the existing products for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/products-get-openapi.md
- name: Gumroad Post Products
  x-api-slug: gumroad
  description: Create a new product for the user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/products-post-openapi.md
- name: Gumroad Delete Products
  x-api-slug: gumroad
  description: Permanently delete a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:id
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsid-delete-openapi.md
- name: Gumroad Get Products
  x-api-slug: gumroad
  description: Retrieve the details of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:id
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsid-get-openapi.md
- name: Gumroad Put Products
  x-api-slug: gumroad
  description: Edit an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:id
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsid-put-openapi.md
- name: Gumroad Put Products Enable
  x-api-slug: gumroad
  description: Enable an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:id/enable
  tags: Products,Enable
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsidenable-put-openapi.md
- name: Gumroad Get Products Custom Fields
  x-api-slug: gumroad
  description: Retrieve all of the existing custom fields for a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/custom_fields
  tags: Products,Custom,Fields
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idcustom-fields-get-openapi.md
- name: Gumroad Post Products Custom Fields
  x-api-slug: gumroad
  description: Create a new custom field for a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/custom_fields
  tags: Products,Custom,Fields
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idcustom-fields-post-openapi.md
- name: Gumroad Put Products Custom Fields Name
  x-api-slug: gumroad
  description: Edit an existing products custom field.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/custom_fields/:name
  tags: Products,Custom,Fields,:name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idcustom-fieldsname-put-openapi.md
- name: Gumroad Get Products Offer Codes
  x-api-slug: gumroad
  description: Retrieve all of the existing offer codes for a product. Either amount_cents
    or percent_off will be returned depending if the offer code is a fixed amount
    off or a percentage off. A universal offer code is one that applies to all products.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idoffer-codes-get-openapi.md
- name: Gumroad Post Products Offer Codes
  x-api-slug: gumroad
  description: Create a new offer code for a product. Default offer code is in cents.
    A universal offer code is one that applies to all products.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idoffer-codes-post-openapi.md
- name: Gumroad Get Products Offer Codes
  x-api-slug: gumroad
  description: Retrieve the details of a specific offer code of a product
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes/:id
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idoffer-codesid-get-openapi.md
- name: Gumroad Put Products Offer Codes
  x-api-slug: gumroad
  description: Edit an existing products offer code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/offer_codes/:id
  tags: Products,Offer,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idoffer-codesid-put-openapi.md
- name: Gumroad Get Products Variant Categories
  x-api-slug: gumroad
  description: Retrieve all of the existing variant categories of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories
  tags: Products,Variant,Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categories-get-openapi.md
- name: Gumroad Post Products Variant Categories
  x-api-slug: gumroad
  description: Create a new variant category on a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories
  tags: Products,Variant,Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categories-post-openapi.md
- name: Gumroad Delete Products Variant Categories
  x-api-slug: gumroad
  description: Permanently delete a variant category of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:id
  tags: Products,Variant,Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesid-delete-openapi.md
- name: Gumroad Get Products Variant Categories
  x-api-slug: gumroad
  description: Retrieve the details of a variant category of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:id
  tags: Products,Variant,Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesid-get-openapi.md
- name: Gumroad Put Products Variant Categories
  x-api-slug: gumroad
  description: Edit a variant category of an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:id
  tags: Products,Variant,Categories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesid-put-openapi.md
- name: Gumroad Post Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Create a new variant of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariants-post-openapi.md
- name: Gumroad Delete Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Permanently delete a variant of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants/:id
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariantsid-delete-openapi.md
- name: Gumroad Get Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Retrieve the details of a variant of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants/:id
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariantsid-get-openapi.md
- name: Gumroad Put Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Edit a variant of an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants/:id
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariantsid-put-openapi.md
- name: Gumroad
  x-api-slug: gumroad
  description: Share and sell exclusive videos directly to your followers. Selling
    stuff has always been a pain. No longer! Get back to creating.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/gumroad/openapi.md
x-common:
- type: x-application-management
  url: https://gumroad.com/settings/developer
- type: x-base
  url: https://api.gumroad.com/
- type: x-blog
  url: http://blog.gumroad.com
- type: x-blog-rss
  url: http://blog.gumroad.com/rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/gumroad
- type: x-developer
  url: https://gumroad.com/developers
- type: x-email
  url: partners@gumroad.com
- type: x-email
  url: support@gumroad.com
- type: x-embeddable
  url: https://gumroad.com/embed
- type: x-github
  url: https://github.com/gumroad
- type: x-pricing
  url: https://gumroad.com/features/pricing
- type: x-privacy
  url: https://gumroad.com/privacy
- type: x-terms-of-service
  url: https://gumroad.com/terms
- type: x-twitter
  url: https://twitter.com/gumroad
- type: x-webhooks
  url: https://gumroad.com/webhooks
- type: x-website
  url: http://gumroad.com
- type: x-website
  url: https://gumroad.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---