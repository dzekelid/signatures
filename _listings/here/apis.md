---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Signatures
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Room Definitions
  x-api-slug: 0tilesial112022001101210030210-js-get
  description: |-
    *Request a list of the name and shape of rooms found within a single venue map tile*

    Room data associated with a map tile is requested by passing `tiles-ia` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesial112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesial112022001101210030210-js-get-openapi.md
- name: Venue Maps - Room Definitions
  x-api-slug: 0tilesial112022001101210030210-js-get
  description: |-
    *Request a list of the name and shape of rooms found within a single venue map tile*

    Room data associated with a map tile is requested by passing `tiles-ia` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesial112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesial112022001101210030210-js-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
- name: Venue Maps - Full Venue Model
  x-api-slug: 1modelsfulldm-12321-js-get
  description: "*Request extended details of places found within a venue*\n\nA full
    model of a venue can be obtained by passing `models-full` in the path of the request
    URL and appending the `id` of the venue in question along with associated authentication
    credentials. \n  \n  Note that the client-side process formatting the JSON response
    may take some time in older browsers.\n\n\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request.\n\n*
    **Signature**  `text`\n \\- Signature\n\n* **Policy**  `text`\n \\- Policy\n\n*
    **Key-Pair-Id**  `text`\n \\- Key-Pair-Id"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelsfulldm-12321-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelsfulldm-12321-js-get-openapi.md
- name: Venue Maps - Full Venue Model
  x-api-slug: 1modelsfulldm-12321-js-get
  description: "*Request extended details of places found within a venue*\n\nA full
    model of a venue can be obtained by passing `models-full` in the path of the request
    URL and appending the `id` of the venue in question along with associated authentication
    credentials. \n  \n  Note that the client-side process formatting the JSON response
    may take some time in older browsers.\n\n\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request.\n\n*
    **Signature**  `text`\n \\- Signature\n\n* **Policy**  `text`\n \\- Policy\n\n*
    **Key-Pair-Id**  `text`\n \\- Key-Pair-Id"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelsfulldm-12321-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelsfulldm-12321-js-get-openapi.md
- name: Venue Maps - Places within a Venue
  x-api-slug: 1modelspoidm-7205-js-get
  description: |-
    *Request a list of the places within a venue*

    Details of the individual places to be found within a venue can be obtained by passing `models-poi` in the path of the request URL and appending the `id` of the venue in question along with associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelspoidm-7205-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelspoidm-7205-js-get-openapi.md
- name: Venue Maps - Places within a Venue
  x-api-slug: 1modelspoidm-7205-js-get
  description: |-
    *Request a list of the places within a venue*

    Details of the individual places to be found within a venue can be obtained by passing `models-poi` in the path of the request URL and appending the `id` of the venue in question along with associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelspoidm-7205-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelspoidm-7205-js-get-openapi.md
- name: Venue Maps - Base64 Encoded Map Tiles
  x-api-slug: 0tilesiab64l112022001101210030210-js-get
  description: |-
    *Request a base64 encoded map tile and associated room definitions with a single request*

    A base64 encoded map tile together with the room definitions, is requested by passing `tiles-ia-b64` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesiab64l112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesiab64l112022001101210030210-js-get-openapi.md
- name: Venue Maps - Room Definitions
  x-api-slug: 0tilesial112022001101210030210-js-get
  description: |-
    *Request a list of the name and shape of rooms found within a single venue map tile*

    Room data associated with a map tile is requested by passing `tiles-ia` in the path of the request URL, along with a known `floor` and `quadkey` and associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesial112022001101210030210-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilesial112022001101210030210-js-get-openapi.md
- name: Venue Maps - Venue Map Tile
  x-api-slug: 0tilespngl112022001101210030210-png-get
  description: |-
    *Request an individual venue map tile*

    In addition to the usual `app_id` and `app_code`, three additional parameters are required for authentication purposes. The `Signature`, `Policy` and `Key-Pair-Id` parameters have been obtained from a prior request to the `Signature` endpoint.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilespngl112022001101210030210-png-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/0tilespngl112022001101210030210-png-get-openapi.md
- name: Venue Maps - Full Venue Model
  x-api-slug: 1modelsfulldm-12321-js-get
  description: "*Request extended details of places found within a venue*\n\nA full
    model of a venue can be obtained by passing `models-full` in the path of the request
    URL and appending the `id` of the venue in question along with associated authentication
    credentials. \n  \n  Note that the client-side process formatting the JSON response
    may take some time in older browsers.\n\n\n\n* **app_id**  `text`\n \\- A 20 byte
    Base64 URL-safe encoded string used for the authentication of the client application.
    \   You must include an `app_id` with every request.\n\n* **app_code**  `text`\n
    \\- A 20 byte Base64 URL-safe encoded string used for the authentication of the
    client application.    You must include an `app_code` with every request.\n\n*
    **Signature**  `text`\n \\- Signature\n\n* **Policy**  `text`\n \\- Policy\n\n*
    **Key-Pair-Id**  `text`\n \\- Key-Pair-Id"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelsfulldm-12321-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelsfulldm-12321-js-get-openapi.md
- name: Venue Maps - Places within a Venue
  x-api-slug: 1modelspoidm-7205-js-get
  description: |-
    *Request a list of the places within a venue*

    Details of the individual places to be found within a venue can be obtained by passing `models-poi` in the path of the request URL and appending the `id` of the venue in question along with associated authentication credentials.



    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.

    * **Signature**  `text`
     \- Signature

    * **Policy**  `text`
     \- Policy

    * **Key-Pair-Id**  `text`
     \- Key-Pair-Id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelspoidm-7205-js-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/signatures/master/_listings/here/1modelspoidm-7205-js-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---