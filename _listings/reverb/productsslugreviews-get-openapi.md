---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Get Products Slug Reviews
  description: View reviews of a comparison shopping page
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /comparison_shopping_pages/{id}/reviews:
    get:
      summary: Get Comparison Shopping Pages Reviews
      description: View reviews of a comparison shopping page
      operationId: getComparisonShoppingPagesReviews
      x-api-path-slug: comparison-shopping-pagesidreviews-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Comparison
      - Shopping
      - Pages
      - Id
      - Reviews
  /listings/{slug}/reviews:
    get:
      summary: Get Listings Slug Reviews
      description: Get listings slug reviews.
      operationId: getListingsSlugReviews
      x-api-path-slug: listingsslugreviews-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Reviews
    post:
      summary: Post Listings Slug Reviews
      description: Create a review for a listing
      operationId: postListingsSlugReviews
      x-api-path-slug: listingsslugreviews-post
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Listings
      - Slug
      - Reviews
  /products/reviews/{id}:
    get:
      summary: Get Products Reviews
      description: Get products reviews.
      operationId: getProductsReviews
      x-api-path-slug: productsreviewsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Products
      - Reviews
      - Id
    put:
      summary: Put Products Reviews
      description: Put products reviews.
      operationId: putProductsReviews
      x-api-path-slug: productsreviewsid-put
      parameters:
      - in: body
        name: body
        description: the content of the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Products
      - Reviews
      - Id
  /products/{slug}/reviews:
    get:
      summary: Get Products Slug Reviews
      description: View reviews of a comparison shopping page
      operationId: getProductsSlugReviews
      x-api-path-slug: productsslugreviews-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Products
      - Slug
      - Reviews
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