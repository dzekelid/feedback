---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Save feedback follow up filter
  version: 1.0.0
  description: Save feedback follow up filter.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/viewing/feedback:
    post:
      summary: Sends viewing feedback to Owner / Landlord
      description: Sends viewing feedback to owner / landlord.
      operationId: DocumentGeneration_ViewingFeedbackBygeneratePackDataContract
      x-api-path-slug: apidocumentgenerationviewingfeedback-post
      parameters:
      - in: body
        name: generatePackDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Sends
      - Viewing
      - Feedback
      - To
      - Owner
      - ""
      - ""
      - Landlord
  /api/list/feedback/followups/savefilter:
    put:
      summary: Save feedback follow up filter
      description: Save feedback follow up filter.
      operationId: List_SaveFeedbackFollowUpFilterByfilter
      x-api-path-slug: apilistfeedbackfollowupssavefilter-put
      parameters:
      - in: body
        name: filter
        description: Filter to save
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Feedback
      - Follow
      - Up
      - Filter
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