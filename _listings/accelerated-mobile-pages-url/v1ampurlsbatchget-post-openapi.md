---
swagger: "2.0"
x-collection-name: Accelerated Mobile Pages URL
x-complete: 0
info:
  title: 'Accelerated Mobile Pages (AMP) URL API '
  description: |-
    Returns AMP URL(s) and equivalent
    [AMP Cache URL(s)](/amp/cache/overview#amp-cache-url-format).
  contact:
    name: Google
    url: https://google.com
  version: v1
host: acceleratedmobilepageurl.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/ampUrls:batchGet:
    post:
      summary: ""
      description: |-
        Returns AMP URL(s) and equivalent
        [AMP Cache URL(s)](/amp/cache/overview#amp-cache-url-format).
      operationId: acceleratedmobilepageurl.ampUrls.batchGet
      x-api-path-slug: v1ampurlsbatchget-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - AMP URLs
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