{
  "info": {
    "name": "Plentymarkets Update a feedback",
    "_postman_id": "7e9562c9-745f-433c-8592-534cc02ab4b6",
    "description": "Updates a feedback. The ID of the feedback must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Feedback",
      "item": [
        {
          "id": "ac64a060-58fb-45e3-8992-9c98fc00ca92",
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
              "id": "d556628f-79cc-46c4-ac2c-4eb0c163fa48"
            }
          ]
        },
        {
          "id": "1c52b258-a655-46ce-8479-551b880eeaf1",
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
              "id": "a73de491-8f1f-4bea-a445-f8af96fdcbd8"
            }
          ]
        },
        {
          "id": "d9ab02a6-766f-4cad-a02e-aa8cb8a07051",
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
              "id": "e48e7821-c383-4b9c-b52e-86de7f383f4a"
            }
          ]
        },
        {
          "id": "62078a1b-bf0c-411f-a533-0b3bf6f07809",
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
              "id": "a399d7f4-943b-4053-9136-a1e175be4452"
            }
          ]
        },
        {
          "id": "802ee774-36ea-44e6-a51e-8064780f68e5",
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
              "id": "478b6ea6-5ad5-497a-8523-d0f7a9091e68"
            }
          ]
        },
        {
          "id": "17b1eaa4-8ad4-4d4f-b84f-434d7536ef59",
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
              "id": "53ba7787-52f1-4ce6-bf37-f602ca5aea39"
            }
          ]
        },
        {
          "id": "104e9570-d375-42b8-a7e8-de49b2048e94",
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
              "id": "7f433164-2129-4c62-9bd1-666363feda07"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "12f37eaf-6e1e-44d1-9dd8-9f1307bf5a9f",
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
              "id": "0db58583-bdb0-48ff-91e4-921b96ebbe6f"
            }
          ]
        },
        {
          "id": "a5b99eda-686a-4df8-b1ba-7d0f42124f84",
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
              "id": "b86c0c48-a083-4c51-9fbf-81e888994727"
            }
          ]
        }
      ]
    }
  ]
}