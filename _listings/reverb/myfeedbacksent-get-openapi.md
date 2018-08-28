---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 0
info:
  title: Reverb Get My Feedback Sent
  description: List of sent feedback
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /feedback/{feedback_id}:
    get:
      summary: Get Feedback Feedback
      description: Get feedback feedback.
      operationId: getFeedbackFeedback
      x-api-path-slug: feedbackfeedback-id-get
      parameters:
      - in: path
        name: feedback_id
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Feedback
      - Id
  /my/feedback/received:
    get:
      summary: Get My Feedback Received
      description: List of received feedback
      operationId: getMyFeedbackReceived
      x-api-path-slug: myfeedbackreceived-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feedback
      - Received
  /my/feedback/sent:
    get:
      summary: Get My Feedback Sent
      description: List of sent feedback
      operationId: getMyFeedbackSent
      x-api-path-slug: myfeedbacksent-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Feedback
      - Sent
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