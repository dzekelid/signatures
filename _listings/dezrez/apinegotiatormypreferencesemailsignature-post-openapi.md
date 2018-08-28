---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Allows you to upload a document for use as email signature
  version: 1.0.0
  description: Allows you to upload a document for use as email signature.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/negotiator/my/preferences/emailsignature:
    post:
      summary: Allows you to upload a document for use as email signature
      description: Allows you to upload a document for use as email signature.
      operationId: Negotiator_UploadEmailSignatureBydocumentDetailsContract
      x-api-path-slug: apinegotiatormypreferencesemailsignature-post
      parameters:
      - in: body
        name: documentDetailsContract
        description: Document details
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Allows
      - You
      - To
      - Upload
      - Documentuse
      - As
      - Email
      - Signature
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---