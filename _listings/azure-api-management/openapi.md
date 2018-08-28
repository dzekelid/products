swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 1
info:
  title: ApiManagementClient
  description: use-these-rest-apis-for-performing-operations-on-user-entity-in-azure-api-management-deployment--the-user-entity-in-api-management-represents-the-developers-that-call-the-apis-of-the-products-to-which-they-are-subscribed-
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