---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API Products Delete
  description: Delete product.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products
  : get:
      summary: Products ListByService
      description: Lists a collection of products in the specified service instance.
      operationId: Products_ListByService
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproducts-get
      parameters:
      - in: query
        name: $filter
        description: '| Field       | Supported operators    | Supported functions                         ||-------------|------------------------|---------------------------------------------||
          id          | ge, le, eq, ne, gt, lt | substringof, contains, startswith,
          endswith || name        | ge, le, eq, ne, gt, lt | substringof, contains,
          startswith, endswith || description | ge, le, eq, ne, gt, lt | substringof,
          contains, startswith, endswith || terms       | ge, le, eq, ne, gt, lt |
          substringof, contains, startswith, endswith || state       | eq                     |                                             |'
      - in: query
        name: expandGroups
        description: When set to true, the response contains an array of groups that
          have visibility to the product
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  : get:
      summary: Products Get
      description: Gets the details of the product specified by its identifier.
      operationId: Products_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
    put:
      summary: Products CreateOrUpdate
      description: Creates or Updates a product.
      operationId: Products_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create or update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Products
    patch:
      summary: Products Update
      description: Update product.
      operationId: Products_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-patch
      parameters:
      - in: header
        name: If-Match
        description: ETag of the Product Entity
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Update parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Products
    delete:
      summary: Products Delete
      description: Delete product.
      operationId: Products_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-delete
      parameters:
      - in: query
        name: deleteSubscriptions
        description: Delete existing subscriptions to the product or not
      - in: header
        name: If-Match
        description: ETag of the Product Entity
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Products
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