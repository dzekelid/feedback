---
swagger: "2.0"
x-collection-name: FraudLabs Pro
x-complete: 1
info:
  title: FraudLabs Pro
  description: online-payment-fraud-detection-service--it-helps-merchants-to-minimize-chargebacks-and-therefore-maximize-the-revenue--it-can-be-used-to-detect-fraud-for-various-kinds-of-payment-method-such-as-credit-card-paypal-cod-and-so-on--please-visit-httpswww-fraudlabspro-com-to-learn-more-
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
---