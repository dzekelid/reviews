---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Get *my* review for the recipe {recipeId}, where "me" is determined
    by standard authentication headers
  description: Get *my* review for the recipe {recipeid}, where "me" is determined
    by standard authentication headers.
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
  /recipe/review/replies/{replyId}:
    delete:
      summary: DELETE a reply to a given review. Authenticated user must be the one
        who originally posted the reply.
      description: Delete a reply to a given review. authenticated user must be the
        one who originally posted the reply..
      operationId: Review_DeleteReply
      x-api-path-slug: recipereviewrepliesreplyid-delete
      parameters:
      - in: path
        name: replyId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - Review
      - Replies
      - ReplyId
    put:
      summary: Update (PUT) a reply to a given review. Authenticated user must be
        the original one that posted the reply.
      description: Update (put) a reply to a given review. authenticated user must
        be the original one that posted the reply..
      operationId: Review_PutReply
      x-api-path-slug: recipereviewrepliesreplyid-put
      parameters:
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: replyId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - Review
      - Replies
      - ReplyId
  /recipe/review/{reviewId}:
    get:
      summary: "Get a given review by string-style ID. This will return a payload
        with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
        top-level reviews with one featured reply underneath. \r\n            Currently,
        the FeaturedReply is the most"
      description: "Get a given review by string-style id. this will return a payload
        with featuredreply, replycount.\r\n            recommended display is to list
        top-level reviews with one featured reply underneath. \r\n            currently,
        the featuredreply is the most."
      operationId: ""
      x-api-path-slug: recipereviewreviewid-get
      parameters:
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - Review
      - ReviewId
    put:
      summary: Update a given top-level review.
      description: Update a given top-level review..
      operationId: Review_Put
      x-api-path-slug: recipereviewreviewid-put
      parameters:
      - in: body
        name: review
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - Review
      - ReviewId
  /recipe/review/{reviewId}/replies:
    get:
      summary: Get a paged list of replies for a given review.
      description: Get a paged list of replies for a given review..
      operationId: Review_GetReplies
      x-api-path-slug: recipereviewreviewidreplies-get
      parameters:
      - in: query
        name: pg
        description: the page (int), starting with 1
      - in: path
        name: reviewId
      - in: query
        name: rpp
        description: results per page (int)
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - Review
      - ReviewId
      - Replies
    post:
      summary: POST a reply to a given review. The date will be set by server. Note
        that replies no longer have star ratings, only top-level reviews do.
      description: Post a reply to a given review. the date will be set by server.
        note that replies no longer have star ratings, only top-level reviews do..
      operationId: Review_PostReply
      x-api-path-slug: recipereviewreviewidreplies-post
      parameters:
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - Review
      - ReviewId
      - Replies
  /recipe/{recipeId}/review:
    get:
      summary: Get *my* review for the recipe {recipeId}, where "me" is determined
        by standard authentication headers
      description: Get *my* review for the recipe {recipeid}, where "me" is determined
        by standard authentication headers.
      operationId: ""
      x-api-path-slug: reciperecipeidreview-get
      parameters:
      - in: path
        name: recipeId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
      - Review
    post:
      summary: Add a new review. Only one review can be provided per {userId, recipeId}
        pair. Otherwise your review will be updated.
      description: Add a new review. only one review can be provided per {userid,
        recipeid} pair. otherwise your review will be updated..
      operationId: Review_Post
      x-api-path-slug: reciperecipeidreview-post
      parameters:
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: recipeId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
      - Review
  /recipe/{recipeId}/review/{reviewId}:
    delete:
      summary: "Delete a review by recipeId and reviewId. DEPRECATED. Please see recipe/review/{reviewId}
        for the preferred method.\r\n            (We are moving from an integer-based
        ID system to a GUID-style string-based ID system for reviews and replies.)"
      description: "Delete a review by recipeid and reviewid. deprecated. please see
        recipe/review/{reviewid} for the preferred method.\r\n            (we are
        moving from an integer-based id system to a guid-style string-based id system
        for reviews and replies.)."
      operationId: Review_Delete
      x-api-path-slug: reciperecipeidreviewreviewid-delete
      parameters:
      - in: path
        name: recipeId
      - in: path
        name: reviewId
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
      - Review
      - ReviewId
    get:
      summary: "Get a given review - DEPRECATED. See recipe/review/{reviewId} for
        the current usage.\r\n            Beginning in January 2017, BigOven moded
        from an integer-based ID system to a GUID-style string-based ID system for
        reviews and replies.\r\n            We"
      description: "Get a given review - deprecated. see recipe/review/{reviewid}
        for the current usage.\r\n            beginning in january 2017, bigoven moded
        from an integer-based id system to a guid-style string-based id system for
        reviews and replies.\r\n            we."
      operationId: ""
      x-api-path-slug: reciperecipeidreviewreviewid-get
      parameters:
      - in: path
        name: recipeId
        description: int
      - in: path
        name: reviewId
        description: int
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
      - Review
      - ReviewId
    put:
      summary: "HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
        PUT for the new endpoint.\r\n            We are moving to a string-based primary
        key system, no longer integers, for reviews and replies."
      description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
        put for the new endpoint.\r\n            we are moving to a string-based primary
        key system, no longer integers, for reviews and replies.."
      operationId: Review_PutLegacy
      x-api-path-slug: reciperecipeidreviewreviewid-put
      parameters:
      - in: path
        name: recipeId
        description: recipeId (int)
      - in: body
        name: review
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: reviewId
        description: reviewId (int)
      responses:
        200:
          description: OK
      tags:
      - Recipes
      - Recipe
      - RecipeId
      - Review
      - ReviewId
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