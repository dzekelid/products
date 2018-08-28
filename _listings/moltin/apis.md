---
name: moltin
x-slug: moltin
description: The comprehensive eCommerce API infrastructure for any platform. Moltin
  handles data storage and eCommerce logic in the cloud so that you can focus on creating
  great customer experiences.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Products
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/apis.md
specificationVersion: "0.14"
apis:
- name: Moltin - Update Product <=> Variations Relationships
  x-api-slug: v2productsproductidrelationshipsvariations-put
  description: '`Product Variation`''s specified in the payload willbe related to
    the `Product` any relatiosnhips to `Product Variation`''s **NOT** specified in
    payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsvariations-put-openapi.md
- name: Moltin - Create Product <=> Variations Relationships
  x-api-slug: v2productsproductidrelationshipsvariations-post
  description: Here you can add and remove `Product Variation`'s to a product. `Product
    Variation`'s specified in the payload willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsvariations-post-openapi.md
- name: Moltin - Delete Product <=> Variations Relationships
  x-api-slug: v2productsproductidrelationshipsvariations-delete
  description: Here you can add and remove `Product Variation`'s to a product. Only
    relationships to `Product Variation`'s specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsvariations-delete-openapi.md
- name: Moltin - Stock transactions for a product
  x-api-slug: v2inventoriesproductidtransactions-get
  description: Stock transactions for a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2inventoriesproductidtransactions-get-openapi.md
- name: Moltin - Create a stock transaction for a product
  x-api-slug: v2inventoriesproductidtransactions-post
  description: Create a stock transaction for a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2inventoriesproductidtransactions-post-openapi.md
- name: Moltin - Get a Product
  x-api-slug: v2productsproductid-get
  description: Get a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductid-get-openapi.md
- name: Moltin - Update a Product
  x-api-slug: v2productsproductid-put
  description: Update a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductid-put-openapi.md
- name: Moltin - Delete a Product
  x-api-slug: v2productsproductid-delete
  description: Delete a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductid-delete-openapi.md
- name: Moltin - Update Product <=> Brands Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-put
  description: Here you can set relations `Brand`'s to a product. The result of this
    request will set relationships between product and the specified brnads in teh
    payload and remove any other relations the product had with brands.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-put-openapi.md
- name: Moltin - Create Product <=> Brands Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-post
  description: Here you can add `Brand`'s to a product. The `Brand`'s found in the
    payload will be added to any other relationships to `Brand`'s present.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-post-openapi.md
- name: Moltin - Delete Products <=> Brands Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-delete
  description: Here you can delete a relationship between a `Product` and `Brand`'s.
    Only those relationshops to `Brand`'s specified in the paylaod will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-delete-openapi.md
- name: Moltin - Get a Product Variation
  x-api-slug: v2variationsvariationid-get
  description: Get a product variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationid-get-openapi.md
- name: Moltin - Update a Product Variation
  x-api-slug: v2variationsvariationid-put
  description: Update a product variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationid-put-openapi.md
- name: Moltin - Delete a Product Variation
  x-api-slug: v2variationsvariationid-delete
  description: Delete a product variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationid-delete-openapi.md
- name: Moltin - Build Child Products
  x-api-slug: v2productsproductidbuild-post
  description: Build child products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidbuild-post-openapi.md
- name: Moltin - Update Product <=> Categories Relationships
  x-api-slug: v2productsproductidrelationshipscategories-put
  description: Here you can update `Categories` to a product. `Categories` specified
    in the payload willbe related to the product any relatiosnhips to `Categories`
    **NOT** specified in payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscategories-put-openapi.md
- name: Moltin - Create Product <=> Categories Relationships
  x-api-slug: v2productsproductidrelationshipscategories-post
  description: Here you can add `Categories` to a product. `Categories` specified
    in the payload willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscategories-post-openapi.md
- name: Moltin - Delete Product <=> Categories Relationships
  x-api-slug: v2productsproductidrelationshipscategories-delete
  description: Here you can delete a relationship between a `Product` and `Category`.
    Only relationships to `Categories` specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscategories-delete-openapi.md
- name: Moltin - Get Product Variations List
  x-api-slug: v2variations-get
  description: Get product variations list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variations-get-openapi.md
- name: Moltin - Create a Product Variation
  x-api-slug: v2variations-post
  description: Create a product variation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variations-post-openapi.md
- name: Moltin - Update a Product Variation Option
  x-api-slug: v2variationsvariationidoptionsoptionid-put
  description: Update a product variation option.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationidoptionsoptionid-put-openapi.md
- name: Moltin - Delete a Product Variation Option
  x-api-slug: v2variationsvariationidoptionsoptionid-delete
  description: Delete a product variation option.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationidoptionsoptionid-delete-openapi.md
- name: Moltin - Update Product Modifier
  x-api-slug: v2variationsvariationidoptionsoptionidmodifiersmodifierid-put
  description: Update product modifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationidoptionsoptionidmodifiersmodifierid-put-openapi.md
- name: Moltin - Delete Product Modifier
  x-api-slug: v2variationsvariationidoptionsoptionidmodifiersmodifierid-delete
  description: Delete product modifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationidoptionsoptionidmodifiersmodifierid-delete-openapi.md
- name: Moltin - Create Product Modifier
  x-api-slug: v2variationsvariationidoptionsoptionidmodifiers-post
  description: Create product modifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationidoptionsoptionidmodifiers-post-openapi.md
- name: Moltin - Get stock for a product
  x-api-slug: v2inventoriesproductid-get
  description: Get stock for a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2inventoriesproductid-get-openapi.md
- name: Moltin - Get Product Attributes
  x-api-slug: v2productsattributes-get
  description: Get product attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsattributes-get-openapi.md
- name: Moltin - Create a new Product
  x-api-slug: v2products-post
  description: Create a new product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2products-post-openapi.md
- name: Moltin - Create a Product Variation Option
  x-api-slug: v2variationsvariationidoptions-post
  description: Create a product variation option.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2variationsvariationidoptions-post-openapi.md
- name: Moltin - Update Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-put
  description: '`File`''s specified in the payload willbe related to the product any
    relatiosnhips to `File`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-put-openapi.md
- name: Moltin - Create Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-post
  description: Here you can add `File`'s to a product. `File`'s specified in the payload
    willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-post-openapi.md
- name: Moltin - Delete Products <=> Files Relationship
  x-api-slug: v2productsproductidrelationshipsfiles-delete
  description: Here you can delete a relationship between a `Product` and `File`'s.
    Only relationships to `File`'s specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-delete-openapi.md
- name: Moltin - Create Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-post
  description: |-
    Here you can add a `Main Image` to a product. The `Main Image` will be a file and that file will be shown as the first image for the product it is related to.

    It's worth noting that you can only have 1 main image so unlike other relationships, you will be passing an object instead of an array in the body.

    In the Object, the type will be `main_image` and the ID will be the ID of the file you wish to make the main image for that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-post-openapi.md
- name: Moltin - Delete Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-delete
  description: |-
    Here you can delete the `Main Image` from a product.

    In the Object payload, the type will be `main_image` and the ID will be the ID of the main image you wish to delete from that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-delete-openapi.md
- name: Moltin - Update Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-put
  description: '`Collection`''s specified in the payload willbe related to the product
    any relatiosnhips to `Collection`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-put-openapi.md
- name: Moltin - Create Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-post
  description: Here you can add `Collection`'s to a product. `Collection`'s specified
    in the payload willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-post-openapi.md
- name: Moltin - Delete Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-delete
  description: Here you can delete a relationship between a `Product` and `Collections`.
    Only relationships to `Collections` specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-delete-openapi.md
- name: Moltin - Get Products List
  x-api-slug: v2products-get
  description: Get products list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2products-get-openapi.md
- name: Moltin - Update Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-put
  description: '`File`''s specified in the payload willbe related to the product any
    relatiosnhips to `File`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-put-openapi.md
- name: Moltin - Create Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-post
  description: Here you can add `File`'s to a product. `File`'s specified in the payload
    willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-post-openapi.md
- name: Moltin - Delete Products <=> Files Relationship
  x-api-slug: v2productsproductidrelationshipsfiles-delete
  description: Here you can delete a relationship between a `Product` and `File`'s.
    Only relationships to `File`'s specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-delete-openapi.md
- name: Moltin - Create Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-post
  description: |-
    Here you can add a `Main Image` to a product. The `Main Image` will be a file and that file will be shown as the first image for the product it is related to.

    It's worth noting that you can only have 1 main image so unlike other relationships, you will be passing an object instead of an array in the body.

    In the Object, the type will be `main_image` and the ID will be the ID of the file you wish to make the main image for that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-post-openapi.md
- name: Moltin - Delete Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-delete
  description: |-
    Here you can delete the `Main Image` from a product.

    In the Object payload, the type will be `main_image` and the ID will be the ID of the main image you wish to delete from that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-delete-openapi.md
- name: Moltin - Update Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-put
  description: '`Collection`''s specified in the payload willbe related to the product
    any relatiosnhips to `Collection`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-put-openapi.md
- name: Moltin - Create Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-post
  description: Here you can add `Collection`'s to a product. `Collection`'s specified
    in the payload willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-post-openapi.md
- name: Moltin - Delete Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-delete
  description: Here you can delete a relationship between a `Product` and `Collections`.
    Only relationships to `Collections` specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-delete-openapi.md
- name: Moltin - Get Products List
  x-api-slug: v2products-get
  description: Get products list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2products-get-openapi.md
- name: Moltin - Get Products List
  x-api-slug: v2products-get
  description: Get products list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2products-get-openapi.md
- name: Moltin - Delete Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-delete
  description: Here you can delete a relationship between a `Product` and `Collections`.
    Only relationships to `Collections` specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-delete-openapi.md
- name: Moltin - Delete Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-delete
  description: Here you can delete a relationship between a `Product` and `Collections`.
    Only relationships to `Collections` specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-delete-openapi.md
- name: Moltin - Create Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-post
  description: Here you can add `Collection`'s to a product. `Collection`'s specified
    in the payload willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-post-openapi.md
- name: Moltin - Create Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-post
  description: Here you can add `Collection`'s to a product. `Collection`'s specified
    in the payload willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-post-openapi.md
- name: Moltin - Update Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-put
  description: '`Collection`''s specified in the payload willbe related to the product
    any relatiosnhips to `Collection`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-put-openapi.md
- name: Moltin - Update Products <=> Collections Relationships
  x-api-slug: v2productsproductidrelationshipscollections-put
  description: '`Collection`''s specified in the payload willbe related to the product
    any relatiosnhips to `Collection`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipscollections-put-openapi.md
- name: Moltin - Delete Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-delete
  description: |-
    Here you can delete the `Main Image` from a product.

    In the Object payload, the type will be `main_image` and the ID will be the ID of the main image you wish to delete from that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-delete-openapi.md
- name: Moltin - Delete Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-delete
  description: |-
    Here you can delete the `Main Image` from a product.

    In the Object payload, the type will be `main_image` and the ID will be the ID of the main image you wish to delete from that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-delete-openapi.md
- name: Moltin - Create Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-post
  description: |-
    Here you can add a `Main Image` to a product. The `Main Image` will be a file and that file will be shown as the first image for the product it is related to.

    It's worth noting that you can only have 1 main image so unlike other relationships, you will be passing an object instead of an array in the body.

    In the Object, the type will be `main_image` and the ID will be the ID of the file you wish to make the main image for that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-post-openapi.md
- name: Moltin - Create Products <=> Main Image Relationships
  x-api-slug: v2productsproductidrelationshipsbrands-post
  description: |-
    Here you can add a `Main Image` to a product. The `Main Image` will be a file and that file will be shown as the first image for the product it is related to.

    It's worth noting that you can only have 1 main image so unlike other relationships, you will be passing an object instead of an array in the body.

    In the Object, the type will be `main_image` and the ID will be the ID of the file you wish to make the main image for that product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsbrands-post-openapi.md
- name: Moltin - Delete Products <=> Files Relationship
  x-api-slug: v2productsproductidrelationshipsfiles-delete
  description: Here you can delete a relationship between a `Product` and `File`'s.
    Only relationships to `File`'s specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-delete-openapi.md
- name: Moltin - Delete Products <=> Files Relationship
  x-api-slug: v2productsproductidrelationshipsfiles-delete
  description: Here you can delete a relationship between a `Product` and `File`'s.
    Only relationships to `File`'s specified in the payload will be removed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-delete-openapi.md
- name: Moltin - Create Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-post
  description: Here you can add `File`'s to a product. `File`'s specified in the payload
    willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-post-openapi.md
- name: Moltin - Create Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-post
  description: Here you can add `File`'s to a product. `File`'s specified in the payload
    willbe related to the product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-post-openapi.md
- name: Moltin - Update Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-put
  description: '`File`''s specified in the payload willbe related to the product any
    relatiosnhips to `File`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-put-openapi.md
- name: Moltin - Update Products <=> Files Relationships
  x-api-slug: v2productsproductidrelationshipsfiles-put
  description: '`File`''s specified in the payload willbe related to the product any
    relatiosnhips to `File`''s **NOT** specified in payload will be removed.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/moltin-logo.png
  humanURL: https://moltin.com
  baseURL: https://api.moltin.com//
  tags: Commerce, Target, Commerce, Stack Network, Retail, Kiosk, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/moltin/v2productsproductidrelationshipsfiles-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://mocklab.api.gallery.streamdata.io
- type: x-api-stack
  url: http://moltin.stack.network
- type: x-base
  url: https://api.molt.in/
- type: x-blog
  url: https://molt.in/blog
- type: x-developer
  url: https://molt.in/developers
- type: x-documentation
  url: https://docs.moltin.com/
- type: x-email
  url: support@molt.in
- type: x-github
  url: https://github.com/moltin
- type: x-postman
  url: https://www.getpostman.com/collections/e9bdcde0ccb5a08640e6
- type: x-pricing
  url: https://moltin.com/pricing
- type: x-twitter
  url: https://twitter.com/moltin
- type: x-website
  url: https://moltin.com
- type: x-website
  url: https://molt.in/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---