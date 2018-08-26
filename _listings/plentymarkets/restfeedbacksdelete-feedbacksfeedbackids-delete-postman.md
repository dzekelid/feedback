{
  "info": {
    "name": "Plentymarkets Delete multiple feedbacks",
    "_postman_id": "1406f07c-09d6-42c8-930c-dff8fcdd6f61",
    "description": "Deletes multiple feedbacks. A list with IDs of feedbacks must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Feedback",
      "item": [
        {
          "id": "c67dbc1a-6836-487f-a301-b2d781867846",
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
              "id": "51a294c4-7c55-49bd-9c51-37005cbaadd0"
            }
          ]
        },
        {
          "id": "3cca72f4-f3b3-4fa5-bfee-35d103f87c85",
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
              "id": "e9f02afe-5aee-4b30-bfb3-2197267a9b22"
            }
          ]
        },
        {
          "id": "a4385e08-c6df-4d86-b19c-582e826a513e",
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
              "id": "268280c1-c951-44c3-a44e-4555573e4b6d"
            }
          ]
        },
        {
          "id": "9ebfae1e-ca07-475e-8215-cf6a023c295b",
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
              "id": "50ce76f6-af56-45a4-bd7a-46238e47cdc8"
            }
          ]
        },
        {
          "id": "1dd21b44-343e-47eb-a48d-dee66203b39b",
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
              "id": "b10a1a11-0f36-47f9-8272-855346e67282"
            }
          ]
        },
        {
          "id": "f3dbbe97-8c31-4da8-8808-17641506b593",
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
              "id": "5e78db5a-8732-4b6d-8d07-fec10fe53823"
            }
          ]
        },
        {
          "id": "6bdafc72-bd62-4267-97e6-9eafa4c797e0",
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
              "id": "104662fb-9d15-4c1c-936f-84eb58e08d60"
            }
          ]
        },
        {
          "id": "240bf2dc-38af-4c6a-a5e4-7dcc7a38cb43",
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
              "id": "5ecdee72-9ec4-4079-a2ef-7d21966a1799"
            }
          ]
        },
        {
          "id": "8f8b5b3f-f92d-43ab-8094-7a2b36cc4116",
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
              "id": "3e10793b-5939-4270-a308-9831beb28fb6"
            }
          ]
        },
        {
          "id": "53f7dc36-7972-4107-b0aa-5e2d00fcfe0d",
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
              "id": "755954fa-4f02-4ef5-bb52-4a7befacb8d4"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "815746fe-7daf-422a-808f-b0cb81c05435",
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
              "id": "31a6f6c2-32ea-442e-9634-3eca3d20f311"
            }
          ]
        },
        {
          "id": "ca0fcca6-af6e-49ee-9724-f9dc3e76f6f0",
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
              "id": "46a5002c-a19a-489e-ae73-5381c220d773"
            }
          ]
        },
        {
          "id": "1eb5c953-7fa3-48fc-89f4-804eabbdb685",
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
              "id": "dfe64d3e-121b-40b6-a7ac-f2aea88bce07"
            }
          ]
        },
        {
          "id": "611d76fa-29f3-4deb-9fce-3796c18e0694",
          "name": "getRestFeedbacksFeedbacks",
          "request": {
            "url": "http://example.com/rest/feedbacks/feedbacks",
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
            "description": "Lists feedbacks. The reference type and the reference value must be specified (e.g. the reference type is 'order' and the reference value is the ID of the order)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbe8c933-16b9-4a11-89eb-2812d78b20c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Multiple",
      "item": [
        {
          "id": "4be9d8bf-5c72-4e7f-afe6-7e28e44d15c8",
          "name": "deleteRestFeedbacksDeleteFeedbacksFeedbacks",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/feedbacks/delete_feedbacks/:feedbackIds"
              ],
              "variable": [
                {
                  "id": "feedbackIds",
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
            "description": "Deletes multiple feedbacks. A list with IDs of feedbacks must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9ca37db-4975-4c8b-ba6d-b9a99d0656cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Visibility",
      "item": [
        {
          "id": "de1021e5-1f89-4d60-8ef2-f029a3944abc",
          "name": "putRestFeedbacksFeedbacksVisibility",
          "request": {
            "url": "http://example.com/rest/feedbacks/feedbacks_visibility?feedbackIds=%7B%7D&isVisible=%7B%7D",
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
            "description": "Updates the visibility of multiple feedbacks. A list with IDs of feedbacks must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4541b94d-a6e7-401f-b918-2f1ed4a6c950"
            }
          ]
        }
      ]
    },
    {
      "name": "Migrate",
      "item": [
        {
          "id": "c530141c-6801-424c-991f-751590384e87",
          "name": "postRestFeedbacksMigrate",
          "request": {
            "url": "http://example.com/rest/feedbacks/migrate",
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
            "description": "Migrate legacy feedbacks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4ae17ae-bfac-4fa3-abee-98d6c76dba8b"
            }
          ]
        }
      ]
    }
  ]
}