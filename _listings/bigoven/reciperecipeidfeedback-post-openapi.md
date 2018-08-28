---
swagger: "2.0"
x-collection-name: BigOven
x-complete: 0
info:
  title: Big Oven Feedback on a Recipe -- for internal BigOven editors
  description: Feedback on a recipe -- for internal bigoven editors.
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
  /recipe/{recipeId}/feedback:
    post:
      summary: Feedback on a Recipe -- for internal BigOven editors
      description: Feedback on a recipe -- for internal bigoven editors.
      operationId: Recipe_Feedback
      x-api-path-slug: reciperecipeidfeedback-post
      parameters:
      - in: body
        name: data
        description: The payload for feedback, which includes the field feedback
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
      - Feedback
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