---
swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 0
info:
  title: AWS Simple Email Service API Set Identity Feedback Forwarding Enabled
  version: 1.0.0
  description: Given an identity (an email address or a domain), enables or disables
    whether Amazon SES forwards bounce and complaint notifications as email.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=SetIdentityFeedbackForwardingEnabled:
    get:
      summary: Set Identity Feedback Forwarding Enabled
      description: Given an identity (an email address or a domain), enables or disables
        whether Amazon SES forwards bounce and complaint notifications as email.
      operationId: setIdentityFeedbackForwardingEnabled
      x-api-path-slug: actionsetidentityfeedbackforwardingenabled-get
      parameters:
      - in: query
        name: ForwardingEnabled
        description: Sets whether Amazon SES will forward bounce and complaint notifications
          as email
        type: string
      - in: query
        name: Identity
        description: The identity for which to set bounce and complaint notification
          forwarding
        type: string
      responses:
        200:
          description: OK
      tags:
      - Identity
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