{
  "info": {
    "name": "Plentymarkets Migrate legacy feedbacks",
    "_postman_id": "e58581be-e9a2-4ee9-a823-187ae4803aee",
    "description": "Migrate legacy feedbacks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Feedback",
      "item": [
        {
          "id": "1c56fbfc-df66-4128-a32f-443adf427e48",
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
              "id": "0474fff0-7701-4609-bea4-2d552dba58b9"
            }
          ]
        },
        {
          "id": "7e823e05-43f4-4894-83e6-1a24ad72d926",
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
              "id": "a975247e-860e-4b64-99a4-e8d9c4345c69"
            }
          ]
        },
        {
          "id": "02247f23-8d76-486c-8fb5-d3b2514f7e62",
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
              "id": "f5dc600b-fb3d-4047-91af-b7d222b5fd94"
            }
          ]
        },
        {
          "id": "4552b03a-3d6a-4b32-a63b-a90719d038f2",
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
              "id": "ef2a7d9f-7807-44d3-abfe-cf7c917fa20e"
            }
          ]
        },
        {
          "id": "b334c892-37b3-43c9-8e64-f3be3554432a",
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
              "id": "0e72d9da-00ed-40b7-a227-aed770326a70"
            }
          ]
        },
        {
          "id": "d7ea331a-f661-4b96-bfe6-b9be3c30d582",
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
              "id": "1e473437-c20d-434f-8c14-55444eb2007b"
            }
          ]
        },
        {
          "id": "7e4ed064-052e-4881-861b-a7ac776e1451",
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
              "id": "a6b161d1-7667-416b-b099-2ccf22f63389"
            }
          ]
        },
        {
          "id": "17d8755c-e9cd-410b-83c1-98ad92ec9aaa",
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
              "id": "238e7546-7588-4a52-aeea-c4cb3bcc9752"
            }
          ]
        },
        {
          "id": "bd4dbb89-cd6d-4d55-8b4b-37b9c3f55a4e",
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
              "id": "73c288fb-15d2-42b7-81fb-c54ddc36cea9"
            }
          ]
        },
        {
          "id": "523f1bc4-ca23-4d3b-838f-873b18895fba",
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
              "id": "b37eacbb-3b04-46fd-b142-d47da7ad57ec"
            }
          ]
        }
      ]
    },
    {
      "name": "List",
      "item": [
        {
          "id": "27367322-d963-4ed5-8a80-6e94d20824cf",
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
              "id": "e46f59a4-8023-4061-8857-5efd65002a15"
            }
          ]
        },
        {
          "id": "08e7b65a-588d-401d-988c-c34fe13463b2",
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
              "id": "2a9c4de9-96bd-4315-8bbf-44b2c9666f97"
            }
          ]
        },
        {
          "id": "536da499-559f-43c6-b31a-d971e85f2ea4",
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
              "id": "ef29ad93-1ab0-41e2-8160-a5d66cdb27b2"
            }
          ]
        },
        {
          "id": "f816e4db-8bb1-4b6d-b386-898e6c025cb4",
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
              "id": "bb125250-2152-4671-ba00-7cfd4a0bfba5"
            }
          ]
        }
      ]
    },
    {
      "name": "Multiple",
      "item": [
        {
          "id": "f289328f-df44-4aef-b109-ddbf084cfd05",
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
              "id": "09e5ed53-7724-4b8c-92db-8c0611d403ab"
            }
          ]
        }
      ]
    },
    {
      "name": "Visibility",
      "item": [
        {
          "id": "8a2f5ca3-3204-4dc8-a55d-80139d2529b1",
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
              "id": "68343caa-1bea-4bc7-9de7-45557e41d12b"
            }
          ]
        }
      ]
    },
    {
      "name": "Migrate",
      "item": [
        {
          "id": "5fc47f8a-198d-4d45-a3d6-e4ff61c232a8",
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
              "id": "69c069fc-6117-498e-8ae5-3fc98581bd48"
            }
          ]
        }
      ]
    }
  ]
}