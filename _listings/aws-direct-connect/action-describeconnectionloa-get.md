---
swagger: "2.0"
info:
  title: AWS Direct Connect API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConnectionLoa&k=1:
    get:
      summary: ' Describe Connection Loa '
      description: Returns the LOA-CFA for a Connection
      operationId: describeConnectionLoa
      parameters:
      - in: query
        name: connectionId
        description: ID of the connection
        type: string
      - in: query
        name: loaContentType
        description: A standard media type indicating the content type of the LOA-CFA
          document
        type: string
      - in: query
        name: providerName
        description: The name of the APN partner or service provider who establishes
          connectivity on your behalf
        type: string
      responses:
        200:
          description: OK
      tags:
      - connections
definitions: []
x-collection-name: AWS Direct Connect
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