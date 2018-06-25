---
name: Azure API Management
x-slug: azure-api-management
description: Use Azure API Management as a turnkey solution for publishing APIs to
  external and internal customers. Quickly create consistent and modern API gateways
  for existing back-end services hosted anywhere, secure and protect them from abuse
  and overuse, and get insights into usage and health. Plus, automate and scale developer
  onboarding to help get your API program up and running.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Products
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/apis.md
specificationVersion: "0.14"
apis:
- name: Azure API Management API ApiProducts ListByApis
  x-api-slug: azure-api-management-api
  description: Lists all API associated products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/apis/{apiId}/products
  tags: API Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapisapiidproducts-get-openapi.md
- name: Azure API Management API ApiManagementServices ApplyNetworkConfigurationUpdates
  x-api-slug: azure-api-management-api
  description: Updates the Microsoft.ApiManagement resource running in the Virtual
    network to pick the updated network settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/applynetworkconfigurationupdates
  tags: API Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapplynetworkconfigurationupdates-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameapplynetworkconfigurationupdates-post-openapi.md
- name: Azure API Management API Products ListByService
  x-api-slug: azure-api-management-api
  description: Lists a collection of products in the specified service instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproducts-get-openapi.md
- name: Azure API Management API Products Get
  x-api-slug: azure-api-management-api
  description: Gets the details of the product specified by its identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-get-openapi.md
- name: Azure API Management API Products CreateOrUpdate
  x-api-slug: azure-api-management-api
  description: Creates or Updates a product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-put-openapi.md
- name: Azure API Management API Products Update
  x-api-slug: azure-api-management-api
  description: Update product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-patch-openapi.md
- name: Azure API Management API Products Delete
  x-api-slug: azure-api-management-api
  description: Delete product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/products/{productId}
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameproductsproductid-delete-openapi.md
- name: Azure API Management API
  x-api-slug: azure-api-management-api
  description: Use Azure API Management as a turnkey solution for publishing APIs
    to external and internal customers. Quickly create consistent and modern API gateways
    for existing back-end services hosted anywhere, secure and protect them from abuse
    and overuse, and get insights into usage and health. Plus, automate and scale
    developer onboarding to help get your API program up and running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-api-management.png
  humanURL: https://azure.microsoft.com/en-us/services/api-management/
  baseURL: ://management.azure.com//
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/azure-api-management/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/api-management/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/api-management/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/api-management/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/api-management/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---