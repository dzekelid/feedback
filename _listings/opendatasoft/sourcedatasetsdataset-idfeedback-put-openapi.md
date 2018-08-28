---
swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 0
info:
  title: OpenDataSoft Put Source Datasets Dataset Feedback
  description: Create new feedback entry.
  version: 2.1.0
host: public.opendatasoft.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{source}/datasets/{dataset_id}/feedback:
    put:
      summary: Put Source Datasets Dataset Feedback
      description: Create new feedback entry.
      operationId: sendDatasetFeedback
      x-api-path-slug: sourcedatasetsdataset-idfeedback-put
      parameters:
      - in: body
        name: feedback
        description: Feedback entry
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Source
      - Datasets
      - Dataset
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