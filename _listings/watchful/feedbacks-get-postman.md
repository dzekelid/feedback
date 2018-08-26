{
  "info": {
    "name": "Watchful Get Feedbacks",
    "_postman_id": "552a7bc9-1bc5-4542-809f-a297c6c2babd",
    "description": "Returns a list of feedbacks",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audits",
      "item": [
        {
          "id": "0e7bd086-dd07-4848-94ea-cfa713d13ce0",
          "name": "getAudits",
          "request": {
            "url": "http://watchful.li/api/v1/audits?limit=%7B%7D&limitstart=%7B%7D&order=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of audits"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b1003db-a8e0-494a-9c50-8cdab0320720"
            }
          ]
        },
        {
          "id": "6fac6d45-2c34-4a75-b99a-03824dd9db07",
          "name": "getFieldsAudits",
          "request": {
            "url": "http://watchful.li/api/v1/audits/metadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of fields"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f193efdc-4884-49c9-b6ae-cd8705916ca7"
            }
          ]
        },
        {
          "id": "3d6c95c1-3f7a-46e0-93cb-ab3bbcde24db",
          "name": "getAuditById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "audits/:id"
              ],
              "query": [
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a audit based on ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2aeafb58-e6f0-4d16-8764-1d5687040b89"
            }
          ]
        },
        {
          "id": "7ccfe8a8-8d53-4c06-8608-f56a403ae5d8",
          "name": "deleteAuditById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "audits/:id"
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
            "body": {
              "mode": "raw"
            },
            "description": "Delete a specific audit."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "413a9693-2472-4cbf-a5a0-86f129308a71"
            }
          ]
        }
      ]
    },
    {
      "name": "Extensions",
      "item": [
        {
          "id": "b94bbe0f-b0a0-4011-ab53-a9f6612e38b4",
          "name": "getExtensions",
          "request": {
            "url": "http://watchful.li/api/v1/extensions?ext_name=%7B%7D&ext_prefix=%7B%7D&fields=%7B%7D&limit=%7B%7D&limitstart=%7B%7D&order=%7B%7D&siteids=%7B%7D&version=%7B%7D&vUpdate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list Extensions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fdcc6c3-511d-4d6c-aceb-f70e703c672d"
            }
          ]
        },
        {
          "id": "967a209a-7a50-4f02-a25c-b0158182f023",
          "name": "getFieldsExtensions",
          "request": {
            "url": "http://watchful.li/api/v1/extensions/metadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of fields"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e6fd0c3-a880-4e9f-8d79-61a0820dbc6a"
            }
          ]
        },
        {
          "id": "555e95eb-0269-42a9-bc7a-f4eb43bc49d2",
          "name": "ignoreExtensionUpdate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "extensions/:id/ignore"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Set 'ignore updates' for a given extension / site_id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11086da7-e4f2-4eb0-b3e5-678de6d4f0ef"
            }
          ]
        },
        {
          "id": "b893402a-b1df-4e25-8246-26b50e03fcac",
          "name": "unignoreExtensionUpdate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "extensions/:id/unignore"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Remove 'ignore updates' for a given extension"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57473ae8-1c37-44fd-9df4-e2ed28543951"
            }
          ]
        },
        {
          "id": "867bdce4-175d-4111-8c8e-853262286770",
          "name": "updateExtension",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "extensions/:id/update"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Update the extension on the remote site"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7399e9d8-a3a8-47d5-b7fc-be056a439e00"
            }
          ]
        }
      ]
    },
    {
      "name": "Feedbacks",
      "item": [
        {
          "id": "3ec38a99-578a-4b78-9303-19dd1a8f1117",
          "name": "getFeedbacks",
          "request": {
            "url": "http://watchful.li/api/v1/feedbacks?fields=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of feedbacks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77562185-827d-4c11-b853-166251174179"
            }
          ]
        }
      ]
    }
  ]
}