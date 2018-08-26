---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 1
info:
  title: Etsy
  description: bring-etsys-handmade-marketplace-and-community-into-your-apps-
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
  /users/{user_id}/feedback/as-buyer:
    get:
      summary: Get Users User Feedback As Buyer
      description: Retrieves a set of Feedback objects associated to a User.
      operationId: getUsersUserFeedbackAsBuyer
      x-api-path-slug: usersuser-idfeedbackasbuyer-get
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
      - As-buyer
  /users/{user_id}/feedback/as-seller:
    get:
      summary: Get Users User Feedback As Seller
      description: Retrieves a set of Feedback objects associated to a User.
      operationId: getUsersUserFeedbackAsSeller
      x-api-path-slug: usersuser-idfeedbackasseller-get
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
      - As-seller
---