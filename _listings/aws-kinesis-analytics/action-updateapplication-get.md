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
  /?Action=UpdateApplication:
    get:
      summary: ' Update Application '
      description: Updates an existing Amazon Kinesis Analytics application
      operationId: updateApplication
      parameters:
      - in: query
        name: ApplicationName
        description: Name of the Amazon Kinesis Analytics application to update
        type: string
      - in: query
        name: ApplicationUpdate
        description: Describes application updates
        type: string
      - in: query
        name: CurrentApplicationVersionId
        description: The current application version ID
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