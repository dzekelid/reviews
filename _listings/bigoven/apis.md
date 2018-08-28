---
name: BigOven
x-slug: bigoven
description: Free recipe app for home cooks. Create a meal plan, grocery list and
  more from your favorite recipes. Organize your recipe collection and take it anywhere.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
x-kinRank: "8"
x-alexaRank: "117577"
tags: Reviews
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/apis.md
specificationVersion: "0.14"
apis:
- name: Big Oven - Get paged list of reviews for a recipe. Each review will have at
    most one FeaturedReply, as well as a ReplyCount.
  x-api-slug: reciperecipeidreviews-get
  description: Get paged list of reviews for a recipe. each review will have at most
    one featuredreply, as well as a replycount..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviews-get-openapi.md
- name: Big Oven - DELETE a reply to a given review. Authenticated user must be the
    one who originally posted the reply.
  x-api-slug: recipereviewrepliesreplyid-delete
  description: Delete a reply to a given review. authenticated user must be the one
    who originally posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-delete-openapi.md
- name: Big Oven - Update (PUT) a reply to a given review. Authenticated user must
    be the original one that posted the reply.
  x-api-slug: recipereviewrepliesreplyid-put
  description: Update (put) a reply to a given review. authenticated user must be
    the original one that posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-put-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: Big Oven - Get *my* review for the recipe {recipeId}, where "me" is determined
    by standard authentication headers
  x-api-slug: reciperecipeidreview-get
  description: Get *my* review for the recipe {recipeid}, where "me" is determined
    by standard authentication headers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-get-openapi.md
- name: Big Oven - Add a new review. Only one review can be provided per {userId,
    recipeId} pair. Otherwise your review will be updated.
  x-api-slug: reciperecipeidreview-post
  description: Add a new review. only one review can be provided per {userid, recipeid}
    pair. otherwise your review will be updated..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-post-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: Big Oven - DELETE a reply to a given review. Authenticated user must be the
    one who originally posted the reply.
  x-api-slug: recipereviewrepliesreplyid-delete
  description: Delete a reply to a given review. authenticated user must be the one
    who originally posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-delete-openapi.md
- name: Big Oven - DELETE a reply to a given review. Authenticated user must be the
    one who originally posted the reply.
  x-api-slug: recipereviewrepliesreplyid-delete
  description: Delete a reply to a given review. authenticated user must be the one
    who originally posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-delete-openapi.md
- name: Big Oven - Update (PUT) a reply to a given review. Authenticated user must
    be the original one that posted the reply.
  x-api-slug: recipereviewrepliesreplyid-put
  description: Update (put) a reply to a given review. authenticated user must be
    the original one that posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-put-openapi.md
- name: Big Oven - Update (PUT) a reply to a given review. Authenticated user must
    be the original one that posted the reply.
  x-api-slug: recipereviewrepliesreplyid-put
  description: Update (put) a reply to a given review. authenticated user must be
    the original one that posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-put-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: Big Oven - Get *my* review for the recipe {recipeId}, where "me" is determined
    by standard authentication headers
  x-api-slug: reciperecipeidreview-get
  description: Get *my* review for the recipe {recipeid}, where "me" is determined
    by standard authentication headers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-get-openapi.md
- name: Big Oven - Get *my* review for the recipe {recipeId}, where "me" is determined
    by standard authentication headers
  x-api-slug: reciperecipeidreview-get
  description: Get *my* review for the recipe {recipeid}, where "me" is determined
    by standard authentication headers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-get-openapi.md
- name: Big Oven - Add a new review. Only one review can be provided per {userId,
    recipeId} pair. Otherwise your review will be updated.
  x-api-slug: reciperecipeidreview-post
  description: Add a new review. only one review can be provided per {userid, recipeid}
    pair. otherwise your review will be updated..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-post-openapi.md
- name: Big Oven - Add a new review. Only one review can be provided per {userId,
    recipeId} pair. Otherwise your review will be updated.
  x-api-slug: reciperecipeidreview-post
  description: Add a new review. only one review can be provided per {userid, recipeid}
    pair. otherwise your review will be updated..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-post-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: Big Oven - Add a new review. Only one review can be provided per {userId,
    recipeId} pair. Otherwise your review will be updated.
  x-api-slug: reciperecipeidreview-post
  description: Add a new review. only one review can be provided per {userid, recipeid}
    pair. otherwise your review will be updated..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-post-openapi.md
- name: Big Oven - Get *my* review for the recipe {recipeId}, where "me" is determined
    by standard authentication headers
  x-api-slug: reciperecipeidreview-get
  description: Get *my* review for the recipe {recipeid}, where "me" is determined
    by standard authentication headers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreview-get-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
- name: Big Oven - Update (PUT) a reply to a given review. Authenticated user must
    be the original one that posted the reply.
  x-api-slug: recipereviewrepliesreplyid-put
  description: Update (put) a reply to a given review. authenticated user must be
    the original one that posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-put-openapi.md
- name: Big Oven - DELETE a reply to a given review. Authenticated user must be the
    one who originally posted the reply.
  x-api-slug: recipereviewrepliesreplyid-delete
  description: Delete a reply to a given review. authenticated user must be the one
    who originally posted the reply..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewrepliesreplyid-delete-openapi.md
- name: "Big Oven - HTTP PUT (update) a recipe review. DEPRECATED. Please see recipe/review/{reviewId}
    PUT for the new endpoint.\r\n            We are moving to a string-based primary
    key system, no longer integers, for reviews and replies."
  x-api-slug: reciperecipeidreviewreviewid-put
  description: "Http put (update) a recipe review. deprecated. please see recipe/review/{reviewid}
    put for the new endpoint.\r\n            we are moving to a string-based primary
    key system, no longer integers, for reviews and replies.."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-put-openapi.md
- name: "Big Oven - Get a given review - DEPRECATED. See recipe/review/{reviewId}
    for the current usage.\r\n            Beginning in January 2017, BigOven moded
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.\r\n            We"
  x-api-slug: reciperecipeidreviewreviewid-get
  description: "Get a given review - deprecated. see recipe/review/{reviewid} for
    the current usage.\r\n            beginning in january 2017, bigoven moded from
    an integer-based id system to a guid-style string-based id system for reviews
    and replies.\r\n            we."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-get-openapi.md
- name: "Big Oven - Delete a review by recipeId and reviewId. DEPRECATED. Please see
    recipe/review/{reviewId} for the preferred method.\r\n            (We are moving
    from an integer-based ID system to a GUID-style string-based ID system for reviews
    and replies.)"
  x-api-slug: reciperecipeidreviewreviewid-delete
  description: "Delete a review by recipeid and reviewid. deprecated. please see recipe/review/{reviewid}
    for the preferred method.\r\n            (we are moving from an integer-based
    id system to a guid-style string-based id system for reviews and replies.)."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/reciperecipeidreviewreviewid-delete-openapi.md
- name: Big Oven - POST a reply to a given review. The date will be set by server.
    Note that replies no longer have star ratings, only top-level reviews do.
  x-api-slug: recipereviewreviewidreplies-post
  description: Post a reply to a given review. the date will be set by server. note
    that replies no longer have star ratings, only top-level reviews do..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-post-openapi.md
- name: Big Oven - Get a paged list of replies for a given review.
  x-api-slug: recipereviewreviewidreplies-get
  description: Get a paged list of replies for a given review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewidreplies-get-openapi.md
- name: Big Oven - Update a given top-level review.
  x-api-slug: recipereviewreviewid-put
  description: Update a given top-level review..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-put-openapi.md
- name: "Big Oven - Get a given review by string-style ID. This will return a payload
    with FeaturedReply, ReplyCount.\r\n            Recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            Currently,
    the FeaturedReply is the most"
  x-api-slug: recipereviewreviewid-get
  description: "Get a given review by string-style id. this will return a payload
    with featuredreply, replycount.\r\n            recommended display is to list
    top-level reviews with one featured reply underneath. \r\n            currently,
    the featuredreply is the most."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/379-bigoven.jpg
  humanURL: http://www.bigoven.com
  baseURL: https://api2.bigoven.com//
  tags: Cooking, Food, Nutrition, Recipes, Food, Stack Network, Mobile, Technology,
    internet, API Provider, , Profiles, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/reviews/master/_listings/bigoven/recipereviewreviewid-get-openapi.md
x-common:
- type: x-website
  url: http://www.bigoven.com
- type: x-api-gallery
  url: http://bigcommerce.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bigoven.stack.network
- type: x-base
  url: http://api.bigoven.com/
- type: x-blog
  url: http://blog.bigoven.com/
- type: x-blog-rss
  url: http://blog.bigoven.com/index.php/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/bigoven
- type: x-crunchbase
  url: http://www.crunchbase.com/company/bigoven
- type: x-developer
  url: http://api.bigoven.com
- type: x-documentation
  url: http://api2.bigoven.com/
- type: x-email
  url: support@bigoven.com
- type: x-twitter
  url: https://twitter.com/bigoven
- type: x-website
  url: http://bigoven.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---