swagger: "2.0"
x-collection-name: AngelList
x-complete: 1
info:
  title: AngelList
  description: the-angellist-api-provides-developers-with-a-restful-interface-to-the-angellist-data-set--for-more-information-read-the-oauth-faq-
  termsOfService: https://angel.co/terms
  contact:
    name: AngelList
    url: https://angel.co/api
    email: api@angel.co
  version: v1
host: api.angel.co
basePath: /1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reviews:
    get:
      summary: Get Reviews
      description: Get Reviews
      operationId: reviews
      x-api-path-slug: reviews-get
      parameters:
      - in: query
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Reviews
  /reviews/{review_id}:
    get:
      summary: Get Review
      description: Get Review
      operationId: reviews
      x-api-path-slug: reviewsreview-id-get
      parameters:
      - in: path
        name: review_id
      - in: query
        name: startup_id
      responses:
        200:
          description: OK
      tags:
      - Startups
      - Businesses
      - Reviews