{
  "info": {
    "name": "Dezrez Marks Feedback Follow Up List Filter as deleted",
    "_postman_id": "b12c01ae-45d2-4c63-8530-355a8811bb82",
    "description": "Marks feedback follow up list filter as deleted.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Marks",
      "item": [
        {
          "id": "b00af743-dffc-4aca-8dea-99ae272004fe",
          "name": "List_DeleteFeedbackFollowUpListFilterByid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/list/feedbackfollowups/filters/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Marks feedback follow up list filter as deleted."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c1678c6-ca68-460d-a8b9-a62f1b6bf788"
            }
          ]
        }
      ]
    }
  ]
}