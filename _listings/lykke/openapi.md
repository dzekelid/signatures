swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
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