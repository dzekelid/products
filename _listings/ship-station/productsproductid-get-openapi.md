---
swagger: "2.0"
x-collection-name: Ship Station
x-complete: 0
info:
  title: Ship Station Get Product
  description: ""
  version: 1.0.0
host: ssapi.shipstation.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /products:
    get:
      summary: List Products w/o parameters
      description: ""
      operationId: products.get
      x-api-path-slug: products-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Products
      - W
      - O
      - Parameters
  ? /products?sku={sku}&name={name}&productCategoryId={productCategoryId}&productTypeId={productTypeId}&tagId={tagId}&startDate={startDate}&endDate={endDate}&showInactive={showInactive}&sortBy={sortBy}&sortDir={sortDir}&page={page}&pageSize={pageSize}
  : get:
      summary: List Products with parameters
      description: |-
        Obtains a list of products that match the specified criteria.  All of the available filters are optional.  They do not need to be included in the URL.  If you do include them, here's what the URL may look like:

        Url format with filters:

        ```
        /products?sku={sku}
        &name={name}
        &productCategoryId={productCategoryId}
        &productTypeId={productTypeId}
        &tagId={tagId}
        &startDate={startDate}
        &endDate={endDate}
        &showInactive={showInactive}
        &sortBy={sortBy}
        &sortDir={sortDir}
        &page={page}
        &pageSize={pageSize}
        ```
      operationId: products_sku_sku_name_name_productCategoryId_productCategoryId_productTypeId_productTypeId_tagId_tag
      x-api-path-slug: productsskuskunamenameproductcategoryidproductcategoryidproducttypeidproducttypeidtagidtagidstartdatestartdateenddateenddateshowinactiveshowinactivesortbysortbysortdirsortdirpagepagepagesizepagesize-get
      parameters:
      - in: path
        name: endDate
        description: Returns products that were created before the specified date
      - in: path
        name: name
        description: Returns products that match the specified product name
      - in: path
        name: page
        description: Page number
      - in: path
        name: pageSize
        description: Requested page size
      - in: path
        name: productCategoryId
        description: Returns products that match the specified productCategoryId
      - in: path
        name: productTypeId
        description: Returns products that match the specified productTypeId
      - in: path
        name: showInactive
        description: Specifies whether the list should include inactive products
      - in: path
        name: sku
        description: Returns products that match the specified SKU
      - in: path
        name: sortBy
        description: Sorts the order of the response based off the specified value
      - in: path
        name: sortDir
        description: Sets the direction of the sort order
      - in: path
        name: startDate
        description: Returns products that were created after the specified date
      - in: path
        name: tagId
        description: Returns products that match the specified tagId
      responses:
        200:
          description: OK
      tags:
      - List
      - Products
      - Parameters
  /products/{productId}:
    get:
      summary: Get Product
      description: ""
      operationId: products.productId.get
      x-api-path-slug: productsproductid-get
      parameters:
      - in: path
        name: productId
        description: The system generated identifier for the Product
      responses:
        200:
          description: OK
      tags:
      - Product
    put:
      summary: Update Product
      description: Updates an existing product. This call does not currently support
        partial updates. The entire resource must be provided in the body of the request.
      operationId: products.productId.put
      x-api-path-slug: productsproductid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: productId
        description: The system generated identifier for the Product
      responses:
        200:
          description: OK
      tags:
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