{
  "info": {
    "name": "reverb Get Shops Slug Feedback",
    "_postman_id": "4ca68b32-3c5a-43b5-8b6b-afdcacd76520",
    "description": "Get shops slug feedback.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "b84756b0-8ff5-41c2-81b8-d0e796bed8ad",
          "name": "getMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ee7e04c-19d2-445c-adbf-7f3899ed3336"
            }
          ]
        },
        {
          "id": "c95912a8-5016-42ee-aef3-9f304c5c0de3",
          "name": "postMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3aa7f89f-e316-4506-b083-458b37784879"
            }
          ]
        },
        {
          "id": "1f422bee-294d-423c-91fb-69863d7fa7e4",
          "name": "deleteMyFollowsShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "my/follows/shops/:slug"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete my follows shops slug."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef80b317-33f6-4e71-a12a-3fb015e49d05"
            }
          ]
        }
      ]
    },
    {
      "name": "Shops",
      "item": [
        {
          "id": "0324e78e-7c3e-4e97-914b-301a50bcab90",
          "name": "getShopsStorefronts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:id/storefronts"
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
            "description": "Get storefront details on a shop."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3de486ec-2609-462f-8c8a-a10fa2eba84b"
            }
          ]
        },
        {
          "id": "cb2a9320-65aa-4d1b-96a2-d0efa40ce38f",
          "name": "getShopsShopShippingProfiles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:shop_id/shipping_profiles"
              ],
              "variable": [
                {
                  "id": "shop_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of shipping profiles for your shop"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa347a8f-9015-442c-9ca6-a39c75f82c8e"
            }
          ]
        },
        {
          "id": "487f3642-eb53-4bb1-8312-d176c5556a2e",
          "name": "getShopsSlug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:slug"
              ],
              "query": [
                {
                  "key": "include_listing_count",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get details on a shop."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70502f7b-d4de-4433-a654-194e5136602e"
            }
          ]
        },
        {
          "id": "fa4b7e5a-a045-4fe9-a98a-5a32bb341261",
          "name": "getShopsSlugFeedback",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:slug/feedback"
              ],
              "variable": [
                {
                  "id": "slug",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shops slug feedback."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbecfac7-3a6f-4920-bfbc-bd99f03399d7"
            }
          ]
        }
      ]
    }
  ]
}