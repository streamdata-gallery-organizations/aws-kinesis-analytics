---
swagger: "2.0"
info:
  title: AWS Kinesis Analytics API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteApplication:
    get:
      summary: ' Delete Application '
      description: Deletes the specified application
      operationId: deleteApplication
      parameters:
      - in: query
        name: ApplicationName
        description: Name of the Amazon Kinesis Analytics application to delete
        type: string
      - in: query
        name: CreateTimestamp
        description: You can use the DescribeApplication operation to get this value
        type: string
      responses:
        200:
          description: OK
      tags:
      - applications
definitions: []
x-collection-name: AWS Kinesis Analytics
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