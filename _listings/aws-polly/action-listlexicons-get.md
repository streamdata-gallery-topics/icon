---
swagger: "2.0"
info:
  title: AWS Polly API List Lexicons
  version: 1.0.0
  description: Returns a list of pronunciation lexicons stored in an AWS Region.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListLexicons:
    get:
      summary: ' List Lexicons '
      description: Returns a list of pronunciation lexicons stored in an AWS Region
      operationId: listLexicons
      parameters:
      - in: query
        name: NextToken
        description: An opaque pagination token returned from previous       ListLexicons
          operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - lexicons
definitions: []
x-collection-name: AWS Polly
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