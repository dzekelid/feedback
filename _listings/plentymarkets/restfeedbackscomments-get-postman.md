{
  "info": {
    "name": "Plentymarkets List feedback comments",
    "_postman_id": "14ee8bf4-b955-45b1-8445-33b232266c47",
    "description": "Lists feedback comments.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "8df3704c-464f-454b-9659-d973c79f9604",
          "name": "getRestCommentsReferencetypeReferencevalue",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/comments/:referenceType/:referenceValue"
              ],
              "query": [
                {
                  "key": "isVisibleForContact",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "userId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "referenceType",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "referenceValue",
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
            "description": "Lists comments. The reference type and the reference value must be specified (e.g. the reference type is 'order' and the reference value is the ID of the order)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b344208-f291-48a2-aa9d-a49f10e664f4"
            }
          ]
        },
        {
          "id": "bbb5b763-a052-42cd-bfd1-3e57c05e381e",
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
              "id": "83afbbe4-f7e3-40ef-9bdd-5bfec39bd57b"
            }
          ]
        }
      ]
    }
  ]
}