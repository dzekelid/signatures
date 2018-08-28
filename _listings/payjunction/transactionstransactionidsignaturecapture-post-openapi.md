---
swagger: "2.0"
x-collection-name: PayJunction
x-complete: 0
info:
  title: PayJunction Post Transactions Signature Capture
  description: Capture a signature using the scriptel signature capture
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /transactions/{transactionId}/signature/capture:
    post:
      summary: Post Transactions Signature Capture
      description: Capture a signature using the scriptel signature capture
      operationId: TransactionsSignatureCaptureByTransactionIdPost
      x-api-path-slug: transactionstransactionidsignaturecapture-post
      parameters:
      - in: formData
        name: signature
      - in: path
        name: transactionId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Transactions
      - Signature
      - Capture
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