---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Products
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Apiproducts
  x-api-slug: apigee-edge
  description: Lists all API products by name for an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apiproducts
  tags: Organizations,API,Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproducts-get-openapi.md
- name: Apigee Edge Post Organizations Name Apiproducts
  x-api-slug: apigee-edge
  description: 'Create an API product: a list of API resources combined with Quota
    settings that you can use to deliver customized API bundles to your developers.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apiproducts
  tags: Organizations,API,Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproducts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproducts-post-openapi.md
- name: Apigee Edge Get Organizations Name Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Gets the list of keys/apps/developers for an API product of an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apiproducts/{apiproduct_name}
  tags: Organizations,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproductsapiproduct-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproductsapiproduct-name-get-openapi.md
- name: Apigee Edge Put Organizations Name Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: This method updates an existing API product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apiproducts/{apiproduct_name}
  tags: Organizations,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproductsapiproduct-name-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproductsapiproduct-name-put-openapi.md
- name: Apigee Edge Delete Organizations Name Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Deletes an API product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apiproducts/{apiproduct_name}
  tags: Organizations,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproductsapiproduct-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-nameapiproductsapiproduct-name-delete-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Revokes the association of an API Product with a Developer App's consumer
    key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/apiproducts/{apiproduct_name}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Apps App
    Name Keys Consumer Key Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Removes an API product from a developer app key profile, and thereby
    renders the developer app unable to access the URIs defined in the API product
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/apiproducts/{apiproduct_name}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---