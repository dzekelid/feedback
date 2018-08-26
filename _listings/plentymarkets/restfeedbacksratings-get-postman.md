{
  "info": {
    "name": "Plentymarkets List feedback ratings",
    "_postman_id": "8e70e9c9-f5ca-4618-b130-b8c1cd0faad4",
    "description": "Lists feedback ratings.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Feedback",
      "item": [
        {
          "id": "441a059d-2121-4df5-a721-e99a5df070a3",
          "name": "postRestFeedbacksComment",
          "request": {
            "url": "http://example.com/rest/feedbacks/comment?commentRelationTargetId=%7B%7D&commentRelationTargetTypeId=%7B%7D&message=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a feedback comment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18a4bf60-5a24-412f-b6c7-8cd71c13f8ce"
            }
          ]
        },
        {
          "id": "a63550cc-d76b-48f3-91dd-f84ceef0a6f0",
          "name": "getRestFeedbacksCommentComment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/comment/:commentId"
              ],
              "query": [
                {
                  "key": "feedbackCommentId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "commentId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a feedback comment. The ID of the feedback comment must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46d24fbb-5e45-4215-b6bd-06951c7bfd63"
            }
          ]
        },
        {
          "id": "015d240c-e398-44c8-bf5b-d29d7633997b",
          "name": "deleteRestFeedbacksCommentComment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/comment/:commentId"
              ],
              "query": [
                {
                  "key": "feedbackCommentId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "commentId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a feedback comment. The ID of the feedback comment must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f7828da-b0b6-437e-9cdd-4f142b963eae"
            }
          ]
        },
        {
          "id": "a20d7bd1-cd5b-4473-9f35-5f25f4ca332b",
          "name": "postRestFeedbacksFeedback",
          "request": {
            "url": "http://example.com/rest/feedbacks/feedback?feedbackRelationSourceTypeId=%7B%7D&feedbackRelationTargetId=%7B%7D&feedbackRelationTargetTypeId=%7B%7D&title=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a feedback."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f634d27f-2bf8-4110-a14f-367308d58592"
            }
          ]
        },
        {
          "id": "784a4c88-b324-4776-8b6a-4359491db4bd",
          "name": "getRestFeedbacksFeedbackFeedback",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/feedback/:feedbackId"
              ],
              "variable": [
                {
                  "id": "feedbackId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a feedback. The ID of the feedback must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc721a7f-7e7a-42c0-aeb9-9f40d79250f2"
            }
          ]
        },
        {
          "id": "0af0d214-c2f8-4aaf-b918-49a9924fe2ab",
          "name": "putRestFeedbacksFeedbackFeedback",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/feedback/:feedbackId"
              ],
              "variable": [
                {
                  "id": "feedbackId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Updates a feedback. The ID of the feedback must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3185ad4e-b780-4e74-8d99-a9ff41c88811"
            }
          ]
        },
        {
          "id": "571622c6-5d92-4cbb-8040-f2f0bd1c9f42",
          "name": "deleteRestFeedbacksFeedbackFeedback",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/feedback/:feedbackId"
              ],
              "variable": [
                {
                  "id": "feedbackId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a feedback. The ID of the feedback must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21954e79-0670-4cbc-aa14-8d77a6510e6a"
            }
          ]
        },
        {
          "id": "f9dc092e-a305-4f64-ba26-1a380b20d56b",
          "name": "postRestFeedbacksRating",
          "request": {
            "url": "http://example.com/rest/feedbacks/rating?ratingRelationTargetId=%7B%7D&ratingRelationTargetTypeId=%7B%7D&ratingValue=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a feedback rating."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f66ed87f-4664-4068-b9ea-f312715c18ce"
            }
          ]
        },
        {
          "id": "f114a325-d0b2-4d65-b8db-ed1ff994b186",
          "name": "getRestFeedbacksRatingRating",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/rating/:ratingId"
              ],
              "query": [
                {
                  "key": "feedbackRatingId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "ratingId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a feedback rating. The ID of the feedback rating must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae21052c-f70b-45b4-9075-c0909a9ea3bd"
            }
          ]
        },
        {
          "id": "b7b9f6dc-8f40-488d-956a-f2f9bd8ff661",
          "name": "deleteRestFeedbacksRatingRating",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/rating/:ratingId"
              ],
              "query": [
                {
                  "key": "feedbackRatingId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "ratingId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a feedback rating. The ID of the feedback rating must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db3941fb-61ff-4e34-92a1-16adf64dc844"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "621380a7-b7b7-41bd-81b7-9aac0361dd72",
          "name": "getRestFeedbacksComments",
          "request": {
            "url": "http://example.com/rest/feedbacks/comments",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists feedback comments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d2b738b-b1cc-40af-a7bf-f052e2eca431"
            }
          ]
        },
        {
          "id": "eae94ffa-19fe-4682-8991-9222343cf44e",
          "name": "getRestFeedbacksFeedbackRepliesFeedback",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/feedback/replies/:feedbackId"
              ],
              "variable": [
                {
                  "id": "feedbackId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists feedback replies. The ID of the feedback must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3bd9cea5-9ace-46c3-ba46-da24a1173d65"
            }
          ]
        },
        {
          "id": "fa605e92-7bf1-4821-a1b9-c7bb5a362193",
          "name": "getRestFeedbacksRatings",
          "request": {
            "url": "http://example.com/rest/feedbacks/ratings",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists feedback ratings."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55a042bc-c2d2-4c09-8e14-d4f20cd20297"
            }
          ]
        }
      ]
    }
  ]
}