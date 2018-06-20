---
swagger: "2.0"
x-collection-name: AWS Service Catalog
x-complete: 0
info:
  title: AWS Service Catalog API Terminate Provisioned Product
  version: 1.0.0
  description: Requests termination of an existing ProvisionedProduct object.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateProduct:
    get:
      summary: Create Product
      description: Creates a new product.
      operationId: createProduct
      x-api-path-slug: actioncreateproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Description
        description: The text description of the product
        type: string
      - in: query
        name: Distributor
        description: The distributor of the product
        type: string
      - in: query
        name: IdempotencyToken
        description: A token to disambiguate duplicate requests
        type: string
      - in: query
        name: Name
        description: The name of the product
        type: string
      - in: query
        name: Owner
        description: The owner of the product
        type: string
      - in: query
        name: ProductType
        description: The type of the product to create
        type: string
      - in: query
        name: ProvisioningArtifactParameters
        description: Parameters for the provisioning artifact
        type: string
      - in: query
        name: SupportDescription
        description: Support information about the product
        type: string
      - in: query
        name: SupportEmail
        description: Contact email for product support
        type: string
      - in: query
        name: SupportUrl
        description: Contact URL for product support
        type: string
      - in: query
        name: Tags
        description: Tags to associate with the new product
        type: string
      responses:
        1:
          description: Photoset not found - The photoset id passed was not the id
            of avalid photoset owned by the calling user
        2:
          description: Photo not found - The photo id passed was not the id of a valid
            photo owned by the calling user
        95:
          description: SSL is required - SSL is required to access the Flickr API
        96:
          description: Invalid signature - The passed signature was invalid
        97:
          description: Missing signature - The call required signing but no signature
            was sent
        98:
          description: Login failed / Invalid auth token - The login details or auth
            token passed were invalid
        99:
          description: User not logged in / Insufficient permissions - The method
            requires user authentication but the user was not logged in, or the authenticated
            method call did not have the required permissions
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
        200:
          description: OK
      tags:
      - Products
  /?Action=DeleteProduct:
    get:
      summary: Delete Product
      description: Deletes the specified product.
      operationId: deleteProduct
      x-api-path-slug: actiondeleteproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the product for the delete request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProduct:
    get:
      summary: Describe Product
      description: Retrieves information about a specified product.
      operationId: describeProduct
      x-api-path-slug: actiondescribeproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProductAsAdmin:
    get:
      summary: Describe Product As Admin
      description: |-
        Retrieves information about a specified product, run with administrator
                 access.
      operationId: describeProductAsAdmin
      x-api-path-slug: actiondescribeproductasadmin-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The identifier of the product for which to retrieve information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=DescribeProductView:
    get:
      summary: Describe Product View
      description: Retrieves information about a specified product.
      operationId: describeProductView
      x-api-path-slug: actiondescribeproductview-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Id
        description: The ProductViewId of the product to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=ProvisionProduct:
    get:
      summary: Provision Product
      description: Requests a Provision of a specified product.
      operationId: provisionProduct
      x-api-path-slug: actionprovisionproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: NotificationArns
        description: Passed to CloudFormation
        type: string
      - in: query
        name: PathId
        description: The identifier of the path for this products provisioning
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisionedProductName
        description: A user-friendly name to identify the ProvisionedProduct object
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The provisioning artifact identifier for this product
        type: string
      - in: query
        name: ProvisioningParameters
        description: Parameters specified by the administrator that are required for
          provisioning the         product
        type: string
      - in: query
        name: ProvisionToken
        description: An idempotency token that uniquely identifies the provisioning
          request
        type: string
      - in: query
        name: Tags
        description: A list of tags to use as provisioning options
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=ScanProvisionedProducts:
    get:
      summary: Scan Provisioned Products
      description: |-
        Returns a paginated list of all the ProvisionedProduct objects that are currently
                 available (not terminated).
      operationId: scanProvisionedProducts
      x-api-path-slug: actionscanprovisionedproducts-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: AccessLevelFilter
        description: The access level for obtaining results
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioned Products
  /?Action=SearchProducts:
    get:
      summary: Search Products
      description: |-
        Returns a paginated list all of the Products objects to which the caller
                 has access.
      operationId: searchProducts
      x-api-path-slug: actionsearchproducts-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Filters
        description: The list of filters with which to limit search results
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      - in: query
        name: SortBy
        description: The sort field specifier
        type: string
      - in: query
        name: SortOrder
        description: The sort order specifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=SearchProductsAsAdmin:
    get:
      summary: Search Products As Admin
      description: |-
        Retrieves summary and status information about all products created within the
                 caller's account.
      operationId: searchProductsAsAdmin
      x-api-path-slug: actionsearchproductsasadmin-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: Filters
        description: The list of filters with which to limit search results
        type: string
      - in: query
        name: PageSize
        description: The maximum number of items to return in the results
        type: string
      - in: query
        name: PageToken
        description: The page token of the first page retrieved
        type: string
      - in: query
        name: PortfolioId
        description: The portfolio identifier
        type: string
      - in: query
        name: ProductSource
        description: Access level of the source of the product
        type: string
      - in: query
        name: SortBy
        description: The sort field specifier
        type: string
      - in: query
        name: SortOrder
        description: The sort order specifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Products
  /?Action=TerminateProvisionedProduct:
    get:
      summary: Terminate Provisioned Product
      description: Requests termination of an existing ProvisionedProduct object.
      operationId: terminateProvisionedProduct
      x-api-path-slug: actionterminateprovisionedproduct-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: IgnoreErrors
        description: If set to true, AWS Service Catalog stops managing the specified
          ProvisionedProduct object even         if it cannot delete the underlying
          resources
        type: string
      - in: query
        name: ProvisionedProductId
        description: The identifier of the ProvisionedProduct object to terminate
        type: string
      - in: query
        name: ProvisionedProductName
        description: The name of the ProvisionedProduct object to terminate
        type: string
      - in: query
        name: TerminateToken
        description: An idempotency token that uniquely identifies the termination
          request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioned Products
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