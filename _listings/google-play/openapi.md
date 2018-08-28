swagger: "2.0"
x-collection-name: Google Play
x-complete: 1
info:
  title: Google Play
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{packageName}/reviews:
    get:
      summary: Get Reviews
      description: Returns a list of reviews. Only reviews from last week will be
        returned.
      operationId: androidpublisher.reviews.list
      x-api-path-slug: packagenamereviews-get
      parameters:
      - in: query
        name: maxResults
      - in: path
        name: packageName
        description: Unique identifier for the Android app for which we want reviews;
          for example, com
      - in: query
        name: startIndex
      - in: query
        name: token
      - in: query
        name: translationLanguage
      responses:
        200:
          description: OK
      tags:
      - Reviews
  /{packageName}/reviews/{reviewId}:
    get:
      summary: Get Review
      description: Returns a single review.
      operationId: androidpublisher.reviews.get
      x-api-path-slug: packagenamereviewsreviewid-get
      parameters:
      - in: path
        name: packageName
        description: Unique identifier for the Android app for which we want reviews;
          for example, com
      - in: path
        name: reviewId
      - in: query
        name: translationLanguage
      responses:
        200:
          description: OK
      tags:
      - Reviews
  /{packageName}/reviews/{reviewId}:reply:
    post:
      summary: Reply To Review
      description: Reply to a single review, or update an existing reply.
      operationId: androidpublisher.reviews.reply
      x-api-path-slug: packagenamereviewsreviewidreply-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: packageName
        description: Unique identifier for the Android app for which we want reviews;
          for example, com
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Reviews