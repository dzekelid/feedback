{
  "info": {
    "name": "reverb Get Shops Slug Feedback Buyer",
    "_postman_id": "07e6059e-2ca8-4fd5-ad58-aeb4e61fab2c",
    "description": "Get seller's feedback as a buyer",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "e7b419be-a894-4e2d-91a5-8cec1a9170c3",
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
              "id": "973cdd4f-167e-44a7-8b32-3a172ad2925a"
            }
          ]
        },
        {
          "id": "009d9c94-1cae-4486-a751-f0362a0dc991",
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
              "id": "25d94588-280f-4085-909c-d54081973098"
            }
          ]
        },
        {
          "id": "d89a1743-a8cc-4ae8-89db-3f4701739df8",
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
              "id": "e23e7870-0a6e-4daa-bd21-0b65fd81457f"
            }
          ]
        }
      ]
    },
    {
      "name": "Shops",
      "item": [
        {
          "id": "8f95bc41-87af-42c7-aeca-6e1893573482",
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
              "id": "59083752-20c2-4820-a3a6-7805fa0f694e"
            }
          ]
        },
        {
          "id": "59399a33-f713-401c-8317-58468771b0e0",
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
              "id": "710a03f1-e987-4e97-a6e4-5d4db6fe5c66"
            }
          ]
        },
        {
          "id": "4816bb06-135b-486b-a49d-64cf269952c6",
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
              "id": "dbc26839-815c-4d3d-96cc-ab880bee4264"
            }
          ]
        },
        {
          "id": "943235aa-3d3c-490c-905c-f2f047fe89e3",
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
              "id": "9b28c560-1b6e-40f6-8e64-0ca162364ec7"
            }
          ]
        },
        {
          "id": "438e7386-4de4-4b68-8c9c-4ba37e1536c8",
          "name": "getShopsSlugFeedbackBuyer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:slug/feedback/buyer"
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
            "description": "Get seller's feedback as a buyer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77c311e4-f17c-4a6c-9841-a8d1df092689"
            }
          ]
        }
      ]
    }
  ]
}