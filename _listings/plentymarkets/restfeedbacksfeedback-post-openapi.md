---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Create a feedback
  description: Creates a feedback.
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
  /rest/feedbacks/comment/{commentId}:
    delete:
      summary: Delete a feedback comment
      description: Deletes a feedback comment. The ID of the feedback comment must
        be specified.
      operationId: deleteRestFeedbacksCommentComment
      x-api-path-slug: restfeedbackscommentcommentid-delete
      parameters:
      - in: path
        name: commentId
      - in: query
        name: feedbackCommentId
        description: The ID of the feedback comment
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Comment
    get:
      summary: Get a feedback comment
      description: Gets a feedback comment. The ID of the feedback comment must be
        specified.
      operationId: getRestFeedbacksCommentComment
      x-api-path-slug: restfeedbackscommentcommentid-get
      parameters:
      - in: path
        name: commentId
      - in: query
        name: feedbackCommentId
        description: The ID of the feedback comment
      responses:
        200:
          description: OK
      tags:
      - Feedback
      - Comment
  /rest/feedbacks/comments:
    get:
      summary: List feedback comments
      description: Lists feedback comments.
      operationId: getRestFeedbacksComments
      x-api-path-slug: restfeedbackscomments-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Feedback
      - Comments
  /rest/feedbacks/feedback:
    post:
      summary: Create a feedback
      description: Creates a feedback.
      operationId: postRestFeedbacksFeedback
      x-api-path-slug: restfeedbacksfeedback-post
      parameters:
      - in: query
        name: feedbackRelationSourceTypeId
        description: The type ID of the feedbacks source
      - in: query
        name: feedbackRelationTargetId
        description: The ID of the feedbacks target
      - in: query
        name: feedbackRelationTargetTypeId
        description: The type ID of the feedbacks target
      - in: query
        name: title
        description: Feedback title
      responses:
        200:
          description: OK
      tags:
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