---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Get paged list of reviews for a recipe. Each review will have at
    most one FeaturedReply, as well as a ReplyCount.
  description: Get paged list of reviews for a recipe. each review will have at most
    one featuredreply, as well as a replycount..
  termsOfService: Please see our [terms of service](http://api2.bigoven.com/web/documentation/termsofuse
  version: partner
host: api2.bigoven.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /recipe/{recipeId}/reviews:
    get:
      summary: Get paged list of reviews for a recipe. Each review will have at most
        one FeaturedReply, as well as a ReplyCount.
      description: Get paged list of reviews for a recipe. each review will have at
        most one featuredreply, as well as a replycount..
      operationId: Review_GetReviews
      x-api-path-slug: reciperecipeidreviews-get
      parameters:
      - in: query
        name: pg
        description: the page (int), starting with 1
      - in: path
        name: recipeId
        description: recipe id (int)
      - in: query
        name: rpp
        description: results per page (int)
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
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