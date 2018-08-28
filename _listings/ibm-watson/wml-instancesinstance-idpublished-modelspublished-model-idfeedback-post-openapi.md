---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson Machine Learning Post Wml Instances Instance Published Models
    Published Model Feedback
  description: |-
    Receives the feedback data and stores it in the feedback store
    defined in learning configuration
  version: 1.0.0
basePath: v3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: ibm-watson-ml.mybluemix.net
paths:
  /wml_instances/{instance_id}/published_models/{published_model_id}/feedback:
    post:
      summary: Post Wml Instances Instance Published Models Published Model Feedback
      description: |-
        Receives the feedback data and stores it in the feedback store
        defined in learning configuration
      operationId: receives-the-feedback-data-and-stores-it-in-the-feedback-storedefined-in-learning-configuration
      x-api-path-slug: wml-instancesinstance-idpublished-modelspublished-model-idfeedback-post
      parameters:
      - in: body
        name: feedback_data
        description: The feedback data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Wml
      - Instances
      - Instance
      - Id
      - Published
      - Models
      - Published
      - Model
      - Id
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