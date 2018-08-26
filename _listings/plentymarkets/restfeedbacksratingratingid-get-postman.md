{
  "info": {
    "name": "Plentymarkets Get a feedback rating",
    "_postman_id": "e4e02a09-094d-418f-9c8a-57ae85997231",
    "description": "Gets a feedback rating. The ID of the feedback rating must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Feedback",
      "item": [
        {
          "id": "44c1954e-8e72-444e-b8a2-2cd2bb82174d",
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
              "id": "875b7172-6eee-48eb-87fa-067cff92dfde"
            }
          ]
        },
        {
          "id": "559fb6ae-0bb8-403c-b9c6-de6766191759",
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
              "id": "ae87313d-d3e9-495b-bc4e-d616966548bc"
            }
          ]
        },
        {
          "id": "877028f9-c1d3-4e2e-b4b4-80017601ae55",
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
              "id": "db5fe7c8-9f6c-4a03-bd17-8606f1cb3c5c"
            }
          ]
        },
        {
          "id": "232eef7b-0826-44f6-b360-deffe61ffca7",
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
              "id": "265f7823-3d78-44a0-a7c2-790784de945f"
            }
          ]
        },
        {
          "id": "2ff6f659-708f-40c8-95b3-941c04fc4c7a",
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
              "id": "c4e54051-af1a-41c2-b1ea-713fe51c7300"
            }
          ]
        },
        {
          "id": "41f767ec-a67f-4736-be57-2a147f2ff383",
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
              "id": "aada3ea2-1cab-44be-9f3b-b083447b274c"
            }
          ]
        },
        {
          "id": "e8ef2e50-94fe-48e3-aa76-f45a2ce7ccd5",
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
              "id": "e022327b-bc2b-4e45-9e82-c9b697dd496f"
            }
          ]
        },
        {
          "id": "ec618ed0-0671-43cd-9652-4fdf14cddf11",
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
              "id": "9fb7694d-3f03-4404-bd8a-c41689711ae3"
            }
          ]
        },
        {
          "id": "26c4682f-fb27-40f2-82bf-29f1413fd432",
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
              "id": "34c9da5b-6533-4003-bf51-7c9415930dca"
            }
          ]
        },
        {
          "id": "80df3bde-772d-4305-9ea9-5e8532d87709",
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
              "id": "081ff779-5788-40b7-a689-bb86918c41dc"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "8fb1291d-bba4-49e9-a9e3-552147238f3e",
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
              "id": "60387e1a-4924-44ac-824a-f07a41b08b5a"
            }
          ]
        },
        {
          "id": "75b6a30b-cb3f-4857-8e2c-58ffdbfa1ef6",
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
              "id": "100f09ee-66a3-4ad5-9454-824263cdfd3e"
            }
          ]
        }
      ]
    }
  ]
}