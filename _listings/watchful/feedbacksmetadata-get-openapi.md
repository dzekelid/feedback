---
swagger: "2.0"
x-collection-name: Watchful
x-complete: 0
info:
  title: Watchful Get The List Of Fields
  description: Returns a list of fields
  version: 1.0.0
host: watchful.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /feedbacks:
    get:
      summary: Get Feedbacks
      description: Returns a list of feedbacks
      operationId: getFeedbacks
      x-api-path-slug: feedbacks-get
      parameters:
      - in: query
        name: fields
        description: Fields to return separate by comas (es
      responses:
        200:
          description: OK
      tags:
      - Feedbacks
    post:
      summary: Create A Feedback
      description: Create a feedback
      operationId: createFeedbacks
      x-api-path-slug: feedbacks-post
      parameters:
      - in: body
        name: body
        description: JSON object Feedback
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Feedbacks
  /feedbacks/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: getFieldsFeedbacks
      x-api-path-slug: feedbacksmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Feedbacks
      - Metadata
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