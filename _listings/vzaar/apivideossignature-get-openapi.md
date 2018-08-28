---
swagger: "2.0"
x-collection-name: Vzaar
x-complete: 0
info:
  title: Vzaar API Get Api Videos Signature
  description: nnThis API call allows a user to request a GUID and an AWS S3 signature.
    With these credentials the user will then be able upload a file into vzaar video
    storage area.nnThe response for this must be parsed and used in the Upload step.
    The upload will fail if any of these details are incorrect.nn
  termsOfService: http://vzaar.com/policies
  version: v1
host: vzaar.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/videos/signature:
    get:
      summary: Get Api Videos Signature
      description: nnThis API call allows a user to request a GUID and an AWS S3 signature.
        With these credentials the user will then be able upload a file into vzaar
        video storage area.nnThe response for this must be parsed and used in the
        Upload step. The upload will fail if any of these details are incorrect.nn
      operationId: getApiVeosSignature
      x-api-path-slug: apivideossignature-get
      parameters:
      - in: query
        name: flash_request
        description: Allows you to use a flash uploader
      - in: query
        name: max_file_size
        description: Specifies the maximum file size (in bytes) to limit the upload
          too
      - in: query
        name: success_action_redirect
        description: Specifies if to redirect to a URL after a successful post instead
          of issuing a 201
      responses:
        200:
          description: OK
      tags:
      - Api
      - Videos
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