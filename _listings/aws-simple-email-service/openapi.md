swagger: "2.0"
x-collection-name: AWS Simple Email Service
x-complete: 1
info:
  title: AWS Simple Email Service API
  version: 1.0.0
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