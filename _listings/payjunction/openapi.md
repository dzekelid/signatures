swagger: "2.0"
x-collection-name: PayJunction
x-complete: 1
info:
  title: PayJunction API Basic
  description: todo-add-description
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