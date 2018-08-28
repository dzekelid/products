{
  "info": {
    "name": "Stripe Get Products",
    "_postman_id": "73fb6359-4b0f-451d-8965-b16ec7902de7",
    "description": "Returns a list of your products. The products are returned sorted by creation date, with the most recently created products appearing first.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "products",
      "item": [
        {
          "id": "c68e2515-5834-401f-afae-f83c495bd90b",
          "name": "getProducts",
          "request": {
            "url": "http://api.stripe.com/v1/products?active=%7B%7D&ending_before=%7B%7D&expand=%7B%7D&ids=%7B%7D&limit=%7B%7D&shippable=%7B%7D&starting_after=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of your products"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f8dc0a1-044b-40e2-aea6-cccda964345f"
            }
          ]
        }
      ]
    }
  ]
}