---
swagger: "2.0"
x-collection-name: FraudLabs Pro
x-complete: 0
info:
  title: FraudLabs Pro V1OrderFeedback_POST
  description: Feedback the status of an order transaction.
  version: 1.0.0
host: virtserver.swaggerhub.com
basePath: /fraudlabspro/fraudlabspro/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/order/feedback:
    post:
      summary: V1OrderFeedback_POST
      description: Feedback the status of an order transaction.
      operationId: V1OrderFeedbackPost
      x-api-path-slug: v1orderfeedback-post
      parameters:
      - in: query
        name: action
      - in: query
        name: format
      - in: query
        name: id
      - in: query
        name: key
      - in: query
        name: notes
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Fraud
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