---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API Products ListByService
  description: Lists a collection of products in the specified service instance.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/products
  : get:
      summary: ApiProducts ListByApis
      description: Lists all API associated products.
      operationId: ApiProducts_ListByApis
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidproducts-get
      parameters:
      - in: query
        name: $filter
        description: '| Field | Supported operators    | Supported functions                         ||-------|------------------------|---------------------------------------------||
          name  | ge, le, eq, ne, gt, lt | substringof, contains, startswith, endswith
          |'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Products
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/applynetworkconfigurationupdates
  : post:
      summary: ApiManagementServices ApplyNetworkConfigurationUpdates
      description: Updates the Microsoft.ApiManagement resource running in the Virtual
        network to pick the updated network settings.
      operationId: ApiManagementServices_ApplyNetworkConfigurationUpdates
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapplynetworkconfigurationupdates-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Products
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