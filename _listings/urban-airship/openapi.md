swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 1
info:
  title: Urban Airship
  description: the-urban-airships-api-powers-mobile-applications-with-push-rich-push-inapp-purchases-and-subscription-services-
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /device_tokens/feedback:
    get:
      summary: Get Device Tokens Feedback
      description: Gets what device tokens are now invalid. Apple informs us when
        a push notification is sent to a device that can???t receive it because the
        application has been uninstalled. We mark the device token as inactive and
        immediately stop sending notifications to that device. Once a day is a good
        interval for querying the feedback service, but you can do it more often to
        save on bandwidth from unnecessary notifications. In the response, what does
        marked_inactive_on mean? Apple sends a timestamp for each device token returned
        via the feedback service. Since a device can be off the network for a while,
        this can be a point in the recent past. In order to make this API work smoothly
        for you, we record the timestamp we marked as inactive. This means you only
        need to query for data since the last time you queried. Once a day is a good
        timeframe, or once a week for very small or infrequently used applications.
        A few times a day is good for applications with heavy use.
      operationId: device_tokens.feedback.get
      x-api-path-slug: device-tokensfeedback-get
      parameters:
      - in: query
        name: since
        description: Since timestamp in ISO 8601 format
      responses:
        200:
          description: OK
      tags:
      - Device
      - Tokens
      - Feedback