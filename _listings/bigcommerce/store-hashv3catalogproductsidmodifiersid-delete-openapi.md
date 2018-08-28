---
swagger: "2.0"
x-collection-name: BigCommerce
x-complete: 0
info:
  title: BigCommerce Delete a product's modifier
  description: ""
  version: 1.0.0
host: api.bigcommerce.com
basePath: /stores
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{store-hash}/v3/catalog/products:
    get:
      summary: Retrieve all products with expanded sub-resources
      description: Shows full product data with a single GET request
      operationId: V3CatalogProductsByStoreHashGet
      x-api-path-slug: storehashv3catalogproducts-get
      parameters:
      - in: query
        name: include
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - ""
      - Products
      - Expanded
      - Sub-resources
    delete:
      summary: Delete multiple products
      description: Deletes products that aren't marked as visible using a filter parameter
      operationId: V3CatalogProductsByStoreHashDelete
      x-api-path-slug: storehashv3catalogproducts-delete
      parameters:
      - in: query
        name: is_visible
      - in: path
        name: store-hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Multiple
      - Products
  /{store_hash}/v3/catalog/products/{id}/modifiers/{id}:
    delete:
      summary: Delete a product's modifier
      description: ""
      operationId: V3CatalogProductsModifiersIdByStoreHashAndIdDelete
      x-api-path-slug: store-hashv3catalogproductsidmodifiersid-delete
      parameters:
      - in: path
        name: id
      - in: path
        name: store_hash
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Products
      - Modifier
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