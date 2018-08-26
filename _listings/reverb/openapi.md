---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
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
  /my/orders/awaiting_feedback:
    get:
      summary: Get My Orders Awaiting Feedback
      description: List of orders that need feedback
      operationId: getMyOrdersAwaitingFeedback
      x-api-path-slug: myordersawaiting-feedback-get
      responses:
        200:
          description: OK
      tags:
      - My
      - Orders
      - Awaiting
      - Feedback
  /orders/{order_id}/feedback/buyer:
    get:
      summary: Get Orders Order Feedback Buyer
      description: Feedback details for an order's buyer
      operationId: getOrdersOrderFeedbackBuyer
      x-api-path-slug: ordersorder-idfeedbackbuyer-get
      parameters:
      - in: path
        name: order_id
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Order
      - Id
      - Feedback
      - Buyer
    post:
      summary: Post Orders Order Feedback Buyer
      description: Add feedback about an order's buyer
      operationId: postOrdersOrderFeedbackBuyer
      x-api-path-slug: ordersorder-idfeedbackbuyer-post
      parameters:
      - in: path
        name: order_id
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Order
      - Id
      - Feedback
      - Buyer
  /orders/{order_id}/feedback/seller:
    get:
      summary: Get Orders Order Feedback Seller
      description: Feedback details for an order's seller
      operationId: getOrdersOrderFeedbackSeller
      x-api-path-slug: ordersorder-idfeedbackseller-get
      parameters:
      - in: path
        name: order_id
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Order
      - Id
      - Feedback
      - Seller
    post:
      summary: Post Orders Order Feedback Seller
      description: Add feedback about an order's seller
      operationId: postOrdersOrderFeedbackSeller
      x-api-path-slug: ordersorder-idfeedbackseller-post
      parameters:
      - in: path
        name: order_id
      responses:
        200:
          description: OK
      tags:
      - Orders
      - Order
      - Id
      - Feedback
      - Seller
  /shops/{slug}/feedback:
    get:
      summary: Get Shops Slug Feedback
      description: Get shops slug feedback.
      operationId: getShopsSlugFeedback
      x-api-path-slug: shopsslugfeedback-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
      - Feedback
  /shops/{slug}/feedback/buyer:
    get:
      summary: Get Shops Slug Feedback Buyer
      description: Get seller's feedback as a buyer
      operationId: getShopsSlugFeedbackBuyer
      x-api-path-slug: shopsslugfeedbackbuyer-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
      - Feedback
      - Buyer
  /shops/{slug}/feedback/seller:
    get:
      summary: Get Shops Slug Feedback Seller
      description: Get seller's feedback as a seller
      operationId: getShopsSlugFeedbackSeller
      x-api-path-slug: shopsslugfeedbackseller-get
      parameters:
      - in: path
        name: slug
      responses:
        200:
          description: OK
      tags:
      - Shops
      - Slug
      - Feedback
      - Seller
---