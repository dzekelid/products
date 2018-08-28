---
swagger: "2.0"
x-collection-name: 3dcart
x-complete: 0
info:
  title: 3dcart Get the EProducts from a specific Product
  version: 1.0.0
  description: Get the eproducts from a specific product.
host: apirest.3dcart.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /3dCartWebAPI/v1/Categories/{categoryid}/Products:
    get:
      summary: Get all products from a specific category
      description: Get all products from a specific category.
      operationId: Products_GetAllProductsFromCategory
      x-api-path-slug: 3dcartwebapiv1categoriescategoryidproducts-get
      parameters:
      - in: path
        name: categoryid
        description: ID of the category
      - in: query
        name: categoryspecial
        description: Category Special Flag
      - in: query
        name: costfrom
        description: Cost of a product
      - in: query
        name: costto
        description: Cost of a product
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: freeshipping
        description: Free Shipping Flag
      - in: query
        name: giftcertificate
        description: Gift Certificate Flag
      - in: query
        name: hide
        description: Hide Flag
      - in: query
        name: homespecial
        description: Home Special Flag
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: nonsearchable
        description: Non-Searchable Flag
      - in: query
        name: nontax
        description: Non-Taxable Flag
      - in: query
        name: notforsale
        description: Not For Sale Flag
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: onsale
        description: On Sale Flag
      - in: query
        name: pricefrom
        description: Price of a product
      - in: query
        name: priceto
        description: Price of a product
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rewarddisable
        description: Disable Rewards Flag
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: selfship
        description: Ships by itself Flag
      - in: query
        name: sku
        description: SKU Code of the product
      - in: query
        name: stockfrom
        description: Stock of a product
      - in: query
        name: stockto
        description: Stock of a product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - From
      - Specific
      - Category
  /3dCartWebAPI/v1/Distributors/{distributorid}/Products:
    get:
      summary: Get all products from a specific distributor
      description: Get all products from a specific distributor.
      operationId: Products_GetAllProductsFromDistributor
      x-api-path-slug: 3dcartwebapiv1distributorsdistributoridproducts-get
      parameters:
      - in: query
        name: categoryspecial
        description: Category Special Flag
      - in: query
        name: costfrom
        description: Cost of a product
      - in: query
        name: costto
        description: Cost of a product
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: path
        name: distributorid
        description: ID of the distributor
      - in: query
        name: freeshipping
        description: Free Shipping Flag
      - in: query
        name: giftcertificate
        description: Gift Certificate Flag
      - in: query
        name: hide
        description: Hide Flag
      - in: query
        name: homespecial
        description: Home Special Flag
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: nonsearchable
        description: Non-Searchable Flag
      - in: query
        name: nontax
        description: Non-Taxable Flag
      - in: query
        name: notforsale
        description: Not For Sale Flag
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: onsale
        description: On Sale Flag
      - in: query
        name: pricefrom
        description: Price of a product
      - in: query
        name: priceto
        description: Price of a product
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rewarddisable
        description: Disable Rewards Flag
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: selfship
        description: Ships by itself Flag
      - in: query
        name: sku
        description: SKU Code of the product
      - in: query
        name: stockfrom
        description: Stock of a product
      - in: query
        name: stockto
        description: Stock of a product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - From
      - Specific
      - Distributor
  /3dCartWebAPI/v1/Manufacturers/{manufacturerid}/Products:
    get:
      summary: Get all products from a specific manufacturer
      description: Get all products from a specific manufacturer.
      operationId: Products_GetAllProductsFromManufacturer
      x-api-path-slug: 3dcartwebapiv1manufacturersmanufactureridproducts-get
      parameters:
      - in: query
        name: categoryspecial
        description: Category Special Flag
      - in: query
        name: costfrom
        description: Cost of a product
      - in: query
        name: costto
        description: Cost of a product
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: freeshipping
        description: Free Shipping Flag
      - in: query
        name: giftcertificate
        description: Gift Certificate Flag
      - in: query
        name: hide
        description: Hide Flag
      - in: query
        name: homespecial
        description: Home Special Flag
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: path
        name: manufacturerid
        description: ID of the manufacturer
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: nonsearchable
        description: Non-Searchable Flag
      - in: query
        name: nontax
        description: Non-Taxable Flag
      - in: query
        name: notforsale
        description: Not For Sale Flag
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: onsale
        description: On Sale Flag
      - in: query
        name: pricefrom
        description: Price of a product
      - in: query
        name: priceto
        description: Price of a product
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rewarddisable
        description: Disable Rewards Flag
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: selfship
        description: Ships by itself Flag
      - in: query
        name: sku
        description: SKU Code of the product
      - in: query
        name: stockfrom
        description: Stock of a product
      - in: query
        name: stockto
        description: Stock of a product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - From
      - Specific
      - Manufacturer
  /3dCartWebAPI/v1/Products:
    get:
      summary: Get all products
      description: Get all products.
      operationId: Products_GetAllProducts
      x-api-path-slug: 3dcartwebapiv1products-get
      parameters:
      - in: query
        name: categoryspecial
        description: Category Special Flag
      - in: query
        name: costfrom
        description: Cost of a product
      - in: query
        name: costto
        description: Cost of a product
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: freeshipping
        description: Free Shipping Flag
      - in: query
        name: giftcertificate
        description: Gift Certificate Flag
      - in: query
        name: hide
        description: Hide Flag
      - in: query
        name: homespecial
        description: Home Special Flag
      - in: query
        name: lastupdateend
        description: End Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: lastupdatestart
        description: Start Date that the product was last updated (mm/dd/yyyy hh:mm:ss)
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: nonsearchable
        description: Non-Searchable Flag
      - in: query
        name: nontax
        description: Non-Taxable Flag
      - in: query
        name: notforsale
        description: Not For Sale Flag
      - in: query
        name: offset
        description: Starting point for the return data
      - in: query
        name: onsale
        description: On Sale Flag
      - in: query
        name: pricefrom
        description: Price of a product
      - in: query
        name: priceto
        description: Price of a product
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: query
        name: rewarddisable
        description: Disable Rewards Flag
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: selfship
        description: Ships by itself Flag
      - in: query
        name: sku
        description: SKU Code of the product
      - in: query
        name: stockfrom
        description: Stock of a product
      - in: query
        name: stockto
        description: Stock of a product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
    put:
      summary: This method is used to update multiple products in the database. No
        URL parameters should be included.
      description: This method is used to update multiple products in the database.
        no url parameters should be included..
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1products-put
      parameters:
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: products
        description: A Json or XML object containing the new product(s)
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Multiple
      - Products
      - In
      - Database
      - ""
      - "No"
      - URL
      - Parameters
      - Should
      - Be
      - Included
    post:
      summary: Adds a new product to the system
      description: Adds a new product to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1products-post
      parameters:
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: product
        description: A Json or XML object containing the new product
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Product
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Related:
    get:
      summary: Get the related products from a specific Product
      description: Get the related products from a specific product.
      operationId: Products_GetAllProductRelated
      x-api-path-slug: 3dcartwebapiv1productscatalogidrelated-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Related
      - Products
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of related products from a specific Product
      description: Updates a collection of related products from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidrelated-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: relatedproducts
        description: A Json or XML object containing the new related products
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Related
      - Products
      - From
      - Specific
      - Product
    post:
      summary: Adds a new related product to the system
      description: Adds a new related product to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidrelated-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: relatedproduct
        description: A Json or XML object containing the new related product
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Related
      - Product
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/skuinfo:
    get:
      summary: Get all products (SKUInfo section only)
      description: Get all products (skuinfo section only).
      operationId: Products_GetAllProductsSKUInfo
      x-api-path-slug: 3dcartwebapiv1productscatalogidskuinfo-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: sku
        description: SKU Code of the product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - (SKUInfo
      - Section
      - Only)
  /3dCartWebAPI/v1/Products/{catalogid}/UpSelling:
    get:
      summary: Get the upselling products from a specific Product
      description: Get the upselling products from a specific product.
      operationId: Products_GetAllProductUpSelling
      x-api-path-slug: 3dcartwebapiv1productscatalogidupselling-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Upselling
      - Products
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of upselling items from a specific Product
      description: Updates a collection of upselling items from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidupselling-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      - in: body
        name: upsellingitems
        description: A Json or XML object containing the new upselling items
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Upselling
      - Items
      - From
      - Specific
      - Product
    post:
      summary: Adds a new upselling item to the system
      description: Adds a new upselling item to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidupselling-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      - in: body
        name: upsellingitem
        description: A Json or XML object containing the new upselling item
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Upselling
      - Item
      - To
      - System
  /3dCartWebAPI/v1/Products/skuinfo:
    get:
      summary: Get all products (SKUInfo section only)
      description: Get all products (skuinfo section only).
      operationId: Products_GetAllProductsSKUInfo
      x-api-path-slug: 3dcartwebapiv1productsskuinfo-get
      parameters:
      - in: query
        name: catalogid
        description: Catalog ID
      - in: query
        name: countonly
        description: Count the number of rows only
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: name
        description: Name of the product
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: query
        name: sku
        description: SKU Code of the product
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Products
      - (SKUInfo
      - Section
      - Only)
  /3dCartWebAPI/v1/Orders/{orderid}/Items/{itemindexid}:
    put:
      summary: Updates a specific item from a specific Product
      description: Updates a specific item from a specific product.
      operationId: Orders_Update
      x-api-path-slug: 3dcartwebapiv1ordersorderiditemsitemindexid-put
      parameters:
      - in: body
        name: item
        description: A Json or XML object containing the new item
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: itemindexid
        description: The unique indexID of an Item
      - in: path
        name: orderid
        description: OrderID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Item
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Orders/{orderid}/Questions/{questionanswerindexid}:
    put:
      summary: Updates a specific question from a specific Product
      description: Updates a specific question from a specific product.
      operationId: Orders_Update
      x-api-path-slug: 3dcartwebapiv1ordersorderidquestionsquestionanswerindexid-put
      parameters:
      - in: path
        name: orderid
        description: OrderID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: question
        description: A Json or XML object containing the new question
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: questionanswerindexid
        description: QuestionID
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Question
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Orders/{orderid}/Transactions/{transactionindexid}:
    put:
      summary: Updates a specific transaction from a specific Product
      description: Updates a specific transaction from a specific product.
      operationId: Orders_Update
      x-api-path-slug: 3dcartwebapiv1ordersorderidtransactionstransactionindexid-put
      parameters:
      - in: path
        name: orderid
        description: OrderID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      - in: body
        name: transaction
        description: A Json or XML object containing the new transaction
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: transactionindexid
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Transaction
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}:
    get:
      summary: Get a product
      description: Get a product.
      operationId: Products_GetProduct
      x-api-path-slug: 3dcartwebapiv1productscatalogid-get
      parameters:
      - in: path
        name: catalogid
        description: Catalogid of the item
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Product
    put:
      summary: This method is used to update a single product record in the database.
        The {catalogid} parameter specifies which product record to update.
      description: This method is used to update a single product record in the database.
        the {catalogid} parameter specifies which product record to update..
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: body
        name: product
        description: A Json or XML object containing the new product
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - This
      - Method
      - Is
      - Used
      - To
      - Update
      - Single
      - Product
      - Record
      - In
      - Database
      - ""
      - Catalogid
      - Parameter
      - Specifies
      - Which
      - Product
      - Record
      - To
      - Update
    delete:
      summary: Deletes a product in the system
      description: Deletes a product in the system.
      operationId: Products_Delete
      x-api-path-slug: 3dcartwebapiv1productscatalogid-delete
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Product
      - In
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/AdvancedOptions:
    get:
      summary: Get the advanced options from a specific Product
      description: Get the advanced options from a specific product.
      operationId: Products_GetAllProductAdvancedOptions
      x-api-path-slug: 3dcartwebapiv1productscatalogidadvancedoptions-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Advanced
      - Options
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of advanced options from a specific Product
      description: Updates a collection of advanced options from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidadvancedoptions-put
      parameters:
      - in: body
        name: advancedoptions
        description: A Json or XML object containing the new advanced options
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Advanced
      - Options
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/AdvancedOptions/{advancedoptioncode}:
    put:
      summary: Updates specific advanced options from a specific Product
      description: Updates specific advanced options from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidadvancedoptionsadvancedoptioncode-put
      parameters:
      - in: body
        name: advancedoption
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: advancedoptioncode
        description: AdvancedOptionCode
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Advanced
      - Options
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Categories:
    get:
      summary: Get the categories from a specific Product
      description: Get the categories from a specific product.
      operationId: Products_GetAllProductCategories
      x-api-path-slug: 3dcartwebapiv1productscatalogidcategories-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Categories
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Discount:
    get:
      summary: Get the discounts from a specific Product
      description: Get the discounts from a specific product.
      operationId: Products_GetAllProductDiscount
      x-api-path-slug: 3dcartwebapiv1productscatalogiddiscount-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Discounts
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of discounts from a specific Product
      description: Updates a collection of discounts from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogiddiscount-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: discounts
        description: A Json or XML object containing the new discount
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Discounts
      - From
      - Specific
      - Product
    post:
      summary: Adds a new discount to the system
      description: Adds a new discount to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogiddiscount-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: body
        name: discount
        description: A Json or XML object containing the new discount
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Discount
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Discount/{discountid}:
    put:
      summary: Updates a specific discount from a specific Product
      description: Updates a specific discount from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogiddiscountdiscountid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: discount
        description: A Json or XML object containing the new discounts
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: discountid
        description: DiscountID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Discount
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Distributors:
    get:
      summary: Get the distributors from a specific Product
      description: Get the distributors from a specific product.
      operationId: Products_GetAllProductDistributors
      x-api-path-slug: 3dcartwebapiv1productscatalogiddistributors-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Distributors
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/EProducts:
    get:
      summary: Get the EProducts from a specific Product
      description: Get the eproducts from a specific product.
      operationId: Products_GetAllProductEProducts
      x-api-path-slug: 3dcartwebapiv1productscatalogideproducts-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - EProducts
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of eproducts from a specific Product
      description: Updates a collection of eproducts from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogideproducts-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: eproducts
        description: A Json or XML object containing the new features
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Eproducts
      - From
      - Specific
      - Product
    post:
      summary: Adds a new eproduct to the system
      description: Adds a new eproduct to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogideproducts-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: body
        name: eproduct
        description: A Json or XML object containing the new eproduct
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Eproduct
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/EProducts/{filenumber}:
    put:
      summary: Updates a specific eproduct from a specific Product
      description: Updates a specific eproduct from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogideproductsfilenumber-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: eproduct
        description: A Json or XML object containing the new features
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: filenumber
        description: FileNumber
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Eproduct
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Features:
    get:
      summary: Get the features from a specific Product
      description: Get the features from a specific product.
      operationId: Products_GetAllProductFeatures
      x-api-path-slug: 3dcartwebapiv1productscatalogidfeatures-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Features
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of features from a specific Product
      description: Updates a collection of features from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidfeatures-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: features
        description: A Json or XML object containing the new features
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Features
      - From
      - Specific
      - Product
    post:
      summary: Adds a new feature to the system
      description: Adds a new feature to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidfeatures-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: body
        name: feature
        description: A Json or XML object containing the new feature
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Feature
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Features/{featureid}:
    put:
      summary: Updates a specific feature from a specific Product
      description: Updates a specific feature from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidfeaturesfeatureid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: feature
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: featureid
        description: FeatureID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Feature
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Images:
    get:
      summary: Get the images from a specific Product
      description: Get the images from a specific product.
      operationId: Products_GetAllProductImages
      x-api-path-slug: 3dcartwebapiv1productscatalogidimages-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Images
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of images from a specific Product
      description: Updates a collection of images from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidimages-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: images
        description: A Json or XML object containing the new images
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Images
      - From
      - Specific
      - Product
    post:
      summary: Adds a new image to the system
      description: Adds a new image to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidimages-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: body
        name: image
        description: A Json or XML object containing the new image
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Image
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Images/{imagegalleryid}:
    put:
      summary: Updates a specific image from a specific Product
      description: Updates a specific image from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidimagesimagegalleryid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: image
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: imagegalleryid
        description: ImageGalleryID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Image
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Options:
    get:
      summary: Get the options from a specific Product
      description: Get the options from a specific product.
      operationId: Products_GetAllProductOptions
      x-api-path-slug: 3dcartwebapiv1productscatalogidoptions-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Options
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of options from a specific Product
      description: Updates a collection of options from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidoptions-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: options
        description: A Json or XML object containing the new options
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Options
      - From
      - Specific
      - Product
    post:
      summary: Adds a new OptionSet to the system
      description: Adds a new optionset to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidoptions-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: body
        name: optionset
        description: A Json or XML object containing the new optionset
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - OptionSet
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Options/{optionsetid}:
    put:
      summary: Updates specific options from a specific Product
      description: Updates specific options from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidoptionsoptionsetid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: body
        name: option
        description: A Json or XML object containing the new options
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: optionsetid
        description: OptionSetID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Options
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Related/{relatedindexid}:
    put:
      summary: Updates a specific related product from a specific Product
      description: Updates a specific related product from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidrelatedrelatedindexid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: path
        name: relatedindexid
        description: RelatedIndexID
      - in: body
        name: relatedproduct
        description: A Json or XML object containing the new related products
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Related
      - Product
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/Serials:
    get:
      summary: Get the serials from a specific Product
      description: Get the serials from a specific product.
      operationId: Products_GetAllProductSerials
      x-api-path-slug: 3dcartwebapiv1productscatalogidserials-get
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: query
        name: limit
        description: Maximum number of items that can be returned
      - in: query
        name: offset
        description: Starting point for the return data
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - Serials
      - From
      - Specific
      - Product
    put:
      summary: Updates a collection of serials from a specific Product
      description: Updates a collection of serials from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidserials-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: body
        name: serials
        description: A Json or XML object containing the new serials
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Collection
      - Of
      - Serials
      - From
      - Specific
      - Product
    post:
      summary: Adds a new serial to the system
      description: Adds a new serial to the system.
      operationId: Products_Post
      x-api-path-slug: 3dcartwebapiv1productscatalogidserials-post
      parameters:
      - in: path
        name: catalogid
        description: Catalog ID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: body
        name: serial
        description: A Json or XML object containing the new serial
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - New
      - Serial
      - To
      - System
  /3dCartWebAPI/v1/Products/{catalogid}/Serials/{serialid}:
    put:
      summary: Updates a specific serial from a specific Product
      description: Updates a specific serial from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidserialsserialid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: body
        name: serial
        description: A Json or XML object containing the new features
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: serialid
        description: FeatureID
      - in: header
        name: Token
        description: Token
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Serial
      - From
      - Specific
      - Product
  /3dCartWebAPI/v1/Products/{catalogid}/UpSelling/{upsellingindexid}:
    put:
      summary: Updates a specific Upselling Item from a specific Product
      description: Updates a specific upselling item from a specific product.
      operationId: Products_Update
      x-api-path-slug: 3dcartwebapiv1productscatalogidupsellingupsellingindexid-put
      parameters:
      - in: path
        name: catalogid
        description: CatalogID
      - in: header
        name: PrivateKey
        description: PrivateKey
      - in: header
        name: SecureURL
        description: SecureURL
      - in: header
        name: Token
        description: Token
      - in: path
        name: upsellingindexid
        description: UpSellingIndexID
      - in: body
        name: upsellingitem
        description: A Json or XML object containing the new upselling tem
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Upselling
      - Item
      - From
      - Specific
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