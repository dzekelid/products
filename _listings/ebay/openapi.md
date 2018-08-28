swagger: "2.0"
x-collection-name: eBay
x-complete: 1
info:
  title: Ebay
  description: the-ebay-platform-offers-an-unprecedented-opportunity-to-build-a-new-ebay-business-or-expand-your-current-business-reach-new-customers-and-create-a-potential-new-stream-of-revenue--leverage-the-resources-of-the-ebay-developers-program-to-tap-into-the-ebay-marketplace-with-millions-of-active-users-globally-with-tools-and-services-that-meet-the-diverse-needs-of-buyers-and-sellers-
  contact:
    name: eBay Inc.
  version: 1.0.0
host: api.ebay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /merchandised_product/get_also_bought_products:
    get:
      summary: Get Merchandised Product Get Also Bought Products
      description: 'This call returns products that were also bought when shoppers
        bought the product specified in the request. Showing ''also bought'' products
        inspires up-selling and cross-selling. You specify the product by one of the
        following. epid (eBay Product Id) gtin (Global Trade Item Number) brand (brand
        name such as Nike) plus mpn (Manufacturer''s Part Number) Restrictions For
        a list of supported sites and other restrictions, see API Restrictions. Maximum:
        A maximum of 12 products are returned. The call will return up to 12 products,
        but it can be less than 12. If the number of products found is less than 12,
        the call will return all of the products matching the criteria.'
      operationId: getAlsoBoughtByProduct
      x-api-path-slug: merchandised-productget-also-bought-products-get
      parameters:
      - in: query
        name: brand
        description: The brand of the product
      - in: query
        name: epid
        description: The eBay product identifier of a product
      - in: query
        name: gtin
        description: The unique Global Trade Item Number of the item as defined by
          http://www
      - in: query
        name: mpn
        description: The manufacturer part number of the product
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Merchandised
      - Product
      - ""
      - Also
      - Bought
      - Products
  /merchandised_product/get_also_viewed_products:
    get:
      summary: Get Merchandised Product Get Also Viewed Products
      description: 'This call returns products that were also viewed when shoppers
        viewed the product specified in the request. Showing ''also viewed'' products
        encourages up-selling and cross-selling. You specify the product by one of
        the following. epid (eBay Product Id) gtin (Global Trade Item Number) brand
        (brand name such as Nike) plus mpn (Manufacturer''s Part Number) Restrictions
        For a list of supported sites and other restrictions, see API Restrictions.
        Maximum: A maximum of 12 products are returned. The call will return up to
        12 products, but it can be less than 12. If the number of products found is
        less than 12, the call will return all of the products matching the criteria.'
      operationId: getAlsoViewedByProduct
      x-api-path-slug: merchandised-productget-also-viewed-products-get
      parameters:
      - in: query
        name: brand
        description: The brand of the product
      - in: query
        name: epid
        description: The eBay product identifier of a product
      - in: query
        name: gtin
        description: The unique Global Trade Item Number of the item as defined by
          http://www
      - in: query
        name: mpn
        description: The manufacturer part number of the product
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Merchandised
      - Product
      - ""
      - Also
      - Viewed
      - Products
  /merchandised_product:
    get:
      summary: Get Merchandised Product
      description: This call returns an array of products based on the category and
        metric specified. This includes details of the product, such as the eBay product
        Id (EPID), title, and user reviews and ratings for the product. You can use
        the epid returned by this call in the Browse API search call to retrieve items
        for this product. Restrictions For a list of supported sites and other restrictions,
        see API Restrictions.
      operationId: getMerchandisedProducts
      x-api-path-slug: merchandised-product-get
      parameters:
      - in: query
        name: aspect_filter
        description: The aspect name/value pairs used to further refine product results
      - in: query
        name: category_id
        description: This query parameter limits the products returned to a specific
          eBay category
      - in: query
        name: limit
        description: This value specifies the maximum number of products to return
          in a result set
      - in: query
        name: metric_name
        description: This value filters the result set by the specified metric
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Merchandised
      - Product