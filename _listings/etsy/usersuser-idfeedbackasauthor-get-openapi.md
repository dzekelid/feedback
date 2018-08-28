---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 0
info:
  title: Etsy Get Users User Feedback As Author
  description: Retrieves a set of Feedback objects associated to a User.
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/feedback/as-subject:
    get:
      summary: Get Users User Feedback As Subject
      description: Retrieves a set of Feedback objects associated to a User.
      operationId: getUsersUserFeedbackAsSubject
      x-api-path-slug: usersuser-idfeedbackassubject-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Feedback
      - As-subject
  /users/{user_id}/feedback/as-author:
    get:
      summary: Get Users User Feedback As Author
      description: Retrieves a set of Feedback objects associated to a User.
      operationId: getUsersUserFeedbackAsAuthor
      x-api-path-slug: usersuser-idfeedbackasauthor-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Feedback
      - As-author
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