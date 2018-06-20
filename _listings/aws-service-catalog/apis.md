---
name: AWS Service Catalog
x-slug: aws-service-catalog
description: AWS Service Catalog allows organizations to create and manage catalogs
  of IT services that are approved for use on AWS. These IT services can include everything
  from virtual machine images, servers, software, and databases to complete multi-tier
  application architectures. AWS Service Catalog allows you to centrally manage commonly
  deployed IT services, and helps you achieve consistent governance and meet your
  compliance requirements, while enabling users to quickly deploy only the approved
  IT services they need.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Products
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Service Catalog API Create Product
  x-api-slug: aws-service-catalog-api
  description: Creates a new product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=CreateProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actioncreateproduct-get-openapi.md
- name: AWS Service Catalog API Delete Product
  x-api-slug: aws-service-catalog-api
  description: Deletes the specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DeleteProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actiondeleteproduct-get-openapi.md
- name: AWS Service Catalog API Describe Product
  x-api-slug: aws-service-catalog-api
  description: Retrieves information about a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actiondescribeproduct-get-openapi.md
- name: AWS Service Catalog API Describe Product As Admin
  x-api-slug: aws-service-catalog-api
  description: |-
    Retrieves information about a specified product, run with administrator
             access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProductAsAdmin
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actiondescribeproductasadmin-get-openapi.md
- name: AWS Service Catalog API Describe Product View
  x-api-slug: aws-service-catalog-api
  description: Retrieves information about a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProductView
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actiondescribeproductview-get-openapi.md
- name: AWS Service Catalog API Provision Product
  x-api-slug: aws-service-catalog-api
  description: Requests a Provision of a specified product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ProvisionProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionprovisionproduct-get-openapi.md
- name: AWS Service Catalog API Scan Provisioned Products
  x-api-slug: aws-service-catalog-api
  description: |-
    Returns a paginated list of all the ProvisionedProduct objects that are currently
             available (not terminated).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=ScanProvisionedProducts
  tags: Provisioned Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionscanprovisionedproducts-get-openapi.md
- name: AWS Service Catalog API Search Products
  x-api-slug: aws-service-catalog-api
  description: |-
    Returns a paginated list all of the Products objects to which the caller
             has access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=SearchProducts
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionsearchproducts-get-openapi.md
- name: AWS Service Catalog API Search Products As Admin
  x-api-slug: aws-service-catalog-api
  description: |-
    Retrieves summary and status information about all products created within the
             caller's account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=SearchProductsAsAdmin
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionsearchproductsasadmin-get-openapi.md
- name: AWS Service Catalog API Terminate Provisioned Product
  x-api-slug: aws-service-catalog-api
  description: Requests termination of an existing ProvisionedProduct object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=TerminateProvisionedProduct
  tags: Provisioned Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionterminateprovisionedproduct-get-openapi.md
- name: AWS Service Catalog API Update Product
  x-api-slug: aws-service-catalog-api
  description: Updates an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdateProduct
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionupdateproduct-get-openapi.md
- name: AWS Service Catalog API Update Provisioned Product
  x-api-slug: aws-service-catalog-api
  description: Requests updates to the configuration of an existing ProvisionedProduct
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=UpdateProvisionedProduct
  tags: Provisioned Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/actionupdateprovisionedproduct-get-openapi.md
- name: AWS Service Catalog API
  x-api-slug: aws-service-catalog-api
  description: AWS Service Catalog allows organizations to create and manage catalogs
    of IT services that are approved for use on AWS. These IT services can include
    everything from virtual machine images, servers, software, and databases to complete
    multi-tier application architectures. AWS Service Catalog allows you to centrally
    manage commonly deployed IT services, and helps you achieve consistent governance
    and meet your compliance requirements, while enabling users to quickly deploy
    only the approved IT services they need.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: :///
  tags: Products
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/products/master/_listings/aws-service-catalog/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/servicecatalog/latest/dg/service-catalog-api-overview.html
- type: x-faq
  url: https://aws.amazon.com/servicecatalog/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/servicecatalog/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/servicecatalog/pricing/
- type: x-website
  url: https://aws.amazon.com/servicecatalog/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---