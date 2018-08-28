---
swagger: "2.0"
x-collection-name: AngelList
x-complete: 0
info:
  title: AngelList Get Review
  description: Get Review
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