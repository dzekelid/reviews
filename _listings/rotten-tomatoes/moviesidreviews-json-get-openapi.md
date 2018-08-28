---
swagger: "2.0"
x-collection-name: Rotten Tomatoes
x-complete: 0
info:
  title: Rotten Tomatoes Get Movies Reviews
  description: Get movies reviews.json.
  contact:
    name: Mike Ralphson
    url: https://github.com/mermade/mashery2openapi
    email: mike.ralphson@gmail.com
  version: "1.0"
host: api.rottentomatoes.com
basePath: /api/public/v1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /movies/{id}/reviews.json:
    get:
      summary: Get Movies Reviews
      description: Get movies reviews.json.
      operationId: getMoviesReviews.json
      x-api-path-slug: moviesidreviews-json-get
      parameters:
      - in: query
        name: country
        description: Provides localized data for the selected country (ISO 3166-1
          alpha-2) if available
      - in: path
        name: id
        description: Movie ID
      - in: query
        name: page
        description: The selected page of reviews
      - in: query
        name: page_limit
        description: The number of reviews to show per page
      - in: query
        name: review_type
        description: '3 different review types are possible: all, top_critic and dvd'
      responses:
        200:
          description: OK
      tags:
      - Movies
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