---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Create a feedback comment
  description: Creates a feedback comment.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/feedbacks/comment:
    post:
      summary: Create a feedback comment
      description: Creates a feedback comment.
      operationId: postRestFeedbacksComment
      x-api-path-slug: restfeedbackscomment-post
      parameters:
      - in: query
        name: commentRelationTargetId
        description: The ID of the comments target
      - in: query
        name: commentRelationTargetTypeId
        description: The type ID of the comments target
      - in: query
        name: message
        description: Feedback comment message
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Comment
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