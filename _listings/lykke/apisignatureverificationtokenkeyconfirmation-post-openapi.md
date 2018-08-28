---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Signatureverificationtoken Keyconfirmation
  version: 1.0.0
  description: Add api signatureverificationtoken keyconfirmation.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/signatureVerificationToken/KeyConfirmation:
    get:
      summary: Get API Signatureverificationtoken Keyconfirmation
      description: Get api signatureverificationtoken keyconfirmation.
      operationId: ApiSignatureVerificationTokenKeyConfirmationGet
      x-api-path-slug: apisignatureverificationtokenkeyconfirmation-get
      parameters:
      - in: query
        name: email
      responses:
        200:
          description: OK
      tags:
      - Signatureverificationtoken
      - Keyconfirmation
    post:
      summary: Add API Signatureverificationtoken Keyconfirmation
      description: Add api signatureverificationtoken keyconfirmation.
      operationId: ApiSignatureVerificationTokenKeyConfirmationPost
      x-api-path-slug: apisignatureverificationtokenkeyconfirmation-post
      parameters:
      - in: body
        name: response
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Signatureverificationtoken
      - Keyconfirmation
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