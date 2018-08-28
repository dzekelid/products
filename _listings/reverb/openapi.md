swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products/reviews/{id}:
    get:
      summary: Get Products Reviews
      description: Get products reviews.
      operationId: getProductsReviews
      x-api-path-slug: productsreviewsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Products
      - Reviews
      - Id
    put:
      summary: Put Products Reviews
      description: Put products reviews.
      operationId: putProductsReviews
      x-api-path-slug: productsreviewsid-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Products
      - Reviews
      - Id
  /products/{slug}/reviews:
    get:
      summary: Get Products Slug Reviews
      description: View reviews of a comparison shopping page
      operationId: getProductsSlugReviews
      x-api-path-slug: productsslugreviews-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Products
      - Slug
      - Reviews
    post:
      summary: Post Products Slug Reviews
      description: Create a review for a product
      operationId: postProductsSlugReviews
      x-api-path-slug: productsslugreviews-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Products
      - Slug
      - Reviews
  /categories/{product_type}/{category}:
    get:
      summary: Get Categories Product Type Category
      description: Get categories product type category.
      operationId: getCategoriesProductTypeCategory
      x-api-path-slug: categoriesproduct-typecategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: product_type
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Product
      - Type
      - Category
  /listings/{listing_id}/product_bundle:
    get:
      summary: Get Listings Listing Product Bundle
      description: Find a product bundle attached to a listing
      operationId: getListingsListingProductBundle
      x-api-path-slug: listingslisting-idproduct-bundle-get
      parameters:
      - in: query
        name: for_seller
        description: Pass to see non-live bundles as the seller
      - in: path
        name: listing_id
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Listing
      - Id
      - Product
      - Bundle
  /my/curated_set/product/{product_id}:
    delete:
      summary: Delete My Curated Set Product Product
      description: Delete my curated set product product.
      operationId: deleteMyCuratedSetProductProduct
      x-api-path-slug: mycurated-setproductproduct-id-delete
      parameters:
      - in: path
        name: product_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Curated
      - Set
      - Product
      - Product
      - Id
    post:
      summary: Post My Curated Set Product Product
      description: Post my curated set product product.
      operationId: postMyCuratedSetProductProduct
      x-api-path-slug: mycurated-setproductproduct-id-post
      parameters:
      - in: path
        name: product_id
      responses:
        200:
          description: OK
      tags:
      - My
      - Curated
      - Set
      - Product
      - Product
      - Id