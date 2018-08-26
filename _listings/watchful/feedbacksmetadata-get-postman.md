{
  "info": {
    "name": "Watchful Get The List Of Fields",
    "_postman_id": "4ee1cfd9-59ba-469b-9e6b-f91dee5bfabf",
    "description": "Returns a list of fields",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audits",
      "item": [
        {
          "id": "aa9fc457-9103-46e0-9e8f-6864b3c23a22",
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
              "id": "f3ad1c24-351d-4db2-adb0-ac7987771125"
            }
          ]
        }
      ]
    },
    {
      "name": "Extensions",
      "item": [
        {
          "id": "5f8e4250-71c4-49cb-9982-31eb903ca814",
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
              "id": "ea837201-65c4-41e9-859e-b7218c281593"
            }
          ]
        }
      ]
    },
    {
      "name": "Feedbacks",
      "item": [
        {
          "id": "a60d7836-d0d4-4208-9ff8-9155f143498f",
          "name": "getFieldsFeedbacks",
          "request": {
            "url": "http://watchful.li/api/v1/feedbacks/metadata",
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
              "id": "6dc828a0-c091-4a82-92df-c952819658f2"
            }
          ]
        }
      ]
    }
  ]
}