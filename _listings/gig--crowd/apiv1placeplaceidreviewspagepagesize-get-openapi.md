---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Place Placeid Reviews Page Pagesize
  version: 1.0.0
  description: Get place placeid reviews page pagesize.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/gigme/place/{placeId}/reviews/{page}/{pageSize}:
    get:
      summary: Get Gigme Place Placeid Reviews Page Pagesize
      description: Get gigme place placeid reviews page pagesize.
      operationId: getApiV1GigmePlacePlaceReviewsPagePagesize
      x-api-path-slug: apiv1gigmeplaceplaceidreviewspagepagesize-get
      parameters:
      - in: path
        name: page
      - in: path
        name: pageSize
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeid
      - Reviews
      - Page
      - Pagesize
  /api/v1/gigme/place/reviews/add:
    post:
      summary: Post Gigme Place Reviews Add
      description: Post gigme place reviews add.
      operationId: postApiV1GigmePlaceReviewsAdd
      x-api-path-slug: apiv1gigmeplacereviewsadd-post
      parameters:
      - in: body
        name: reviewRequest
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Reviews
  /api/v1/place/{placeId}/reviews/{page}/{pageSize}:
    get:
      summary: Get Place Placeid Reviews Page Pagesize
      description: Get place placeid reviews page pagesize.
      operationId: getApiV1PlacePlaceReviewsPagePagesize
      x-api-path-slug: apiv1placeplaceidreviewspagepagesize-get
      parameters:
      - in: path
        name: page
      - in: path
        name: pageSize
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Place
      - Placeid
      - Reviews
      - Page
      - Pagesize
  /api/v1/place/reviews/add:
    post:
      summary: Post Place Reviews Add
      description: Post place reviews add.
      operationId: postApiV1PlaceReviewsAdd
      x-api-path-slug: apiv1placereviewsadd-post
      parameters:
      - in: body
        name: reviewRequest
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Place
      - Reviews
  /api/v1/admin/placeReview/{reviewId}/confirm:
    post:
      summary: Post Admin Placereview Reviewid Confirm
      description: Post admin placereview reviewid confirm.
      operationId: postApiV1AdminPlacereviewReviewConfirm
      x-api-path-slug: apiv1adminplacereviewreviewidconfirm-post
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Reviewid
      - Confirm
  /api/v1/admin/placeReview/{reviewId}/reject:
    post:
      summary: Post Admin Placereview Reviewid Reject
      description: Post admin placereview reviewid reject.
      operationId: postApiV1AdminPlacereviewReviewReject
      x-api-path-slug: apiv1adminplacereviewreviewidreject-post
      parameters:
      - in: header
        name: Authorization
      - in: body
        name: reason
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Reviewid
      - Reject
  /api/v1/admin/placeReview/{page}:
    get:
      summary: Get Admin Placereview Page
      description: Get admin placereview page.
      operationId: getApiV1AdminPlacereviewPage
      x-api-path-slug: apiv1adminplacereviewpage-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: page
      - in: query
        name: request.placeName
      - in: query
        name: request.status
      responses:
        200:
          description: OK
      tags:
      - Admin
      - Placereview
      - Page
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