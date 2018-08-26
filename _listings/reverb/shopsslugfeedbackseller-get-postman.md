{
  "info": {
    "name": "reverb Get Shops Slug Feedback Seller",
    "_postman_id": "377f2aae-3759-493e-9345-506638aacc37",
    "description": "Get seller's feedback as a seller",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "My",
      "item": [
        {
          "id": "d7725789-8e05-4f0b-bd6c-04e9bbf2d946",
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
              "id": "e23d0e93-ecfc-4e09-8ac7-9e846b1e61c2"
            }
          ]
        },
        {
          "id": "e2f51232-0cdc-4795-b770-b70a92a3ba54",
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
              "id": "c85bcc4a-5a64-41e3-94db-1d800f512d3f"
            }
          ]
        },
        {
          "id": "4a234f98-aa41-4e73-a0f8-f8005bbae62b",
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
              "id": "7f81c44e-d42c-4863-831c-a6df3970e376"
            }
          ]
        }
      ]
    },
    {
      "name": "Shops",
      "item": [
        {
          "id": "b7acd794-5b6f-4805-abb1-dac34f527c0c",
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
              "id": "c5a021a5-e886-47e2-bc23-e297535d8a87"
            }
          ]
        },
        {
          "id": "a06dbd5e-5153-4374-a80f-89080a0ebd7a",
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
              "id": "a040da81-561f-49d1-8626-bf1efdce6c6d"
            }
          ]
        },
        {
          "id": "5294674e-d607-4452-8cc5-966eb2e532d0",
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
              "id": "65904f80-ad30-43c2-92ce-7685ce31f867"
            }
          ]
        },
        {
          "id": "96b3ac87-179b-402e-a33b-478daa6d06e5",
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
              "id": "ceaedba5-a6fc-4eb2-889a-9d7c62459cb6"
            }
          ]
        },
        {
          "id": "fc44457a-bfcf-4181-860e-71fb4ccbaa91",
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
              "id": "c85ee9bd-dcb1-481b-a84d-52c6a4189beb"
            }
          ]
        },
        {
          "id": "bec4d159-b8b2-4ffe-b3a2-4d3686720174",
          "name": "getShopsSlugFeedbackSeller",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "shops/:slug/feedback/seller"
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
            "description": "Get seller's feedback as a seller"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08523230-0c80-4b0b-a8cb-6717f4b39356"
            }
          ]
        }
      ]
    }
  ]
}