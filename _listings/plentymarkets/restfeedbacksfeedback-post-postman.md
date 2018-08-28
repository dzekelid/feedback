{
  "info": {
    "name": "Plentymarkets Create a feedback",
    "_postman_id": "6d92e349-d554-4aef-94c2-7406866ee092",
    "description": "Creates a feedback.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Feedback",
      "item": [
        {
          "id": "afc80fbf-7cb5-48f0-b4ce-2c1857e2aeee",
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
              "id": "c352a676-3b9f-4afd-b5b1-d26019f98abf"
            }
          ]
        },
        {
          "id": "2cb22d11-8468-48e3-9571-92ca93f4acd3",
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
              "id": "3e22fc74-711f-4912-92e6-5a9635417667"
            }
          ]
        },
        {
          "id": "e2571ff1-e139-44f4-af54-05704a60025e",
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
              "id": "890bd780-974a-406a-abc5-2dae81045f85"
            }
          ]
        },
        {
          "id": "293942ee-1c2b-471c-b7e9-af4ca2648f1b",
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
              "id": "2515a824-49b9-4eee-b270-148c5fd35009"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "dbde90e6-ecb0-4e63-b6c0-a1ab30d961bb",
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
              "id": "641f85f0-16dc-44b8-9368-96535ff48335"
            }
          ]
        }
      ]
    }
  ]
}