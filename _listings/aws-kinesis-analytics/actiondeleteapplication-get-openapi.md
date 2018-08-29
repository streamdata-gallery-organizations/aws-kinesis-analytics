---
swagger: "2.0"
x-collection-name: AWS Kinesis Analytics
x-complete: 0
info:
  title: AWS Kinesis Analytics API Delete Application
  version: 1.0.0
  description: Deletes the specified application.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddApplicationInput:
    get:
      summary: Add Application Input
      description: Adds a streaming source to your Amazon Kinesis application.
      operationId: addApplicationInput
      x-api-path-slug: actionaddapplicationinput-get
      parameters:
      - in: query
        name: ApplicationName
        description: Name of your existing Amazon Kinesis Analytics application to
          which you want to add the streaming source
        type: string
      - in: query
        name: CurrentApplicationVersionId
        description: Current version of your Amazon Kinesis Analytics application
        type: string
      - in: query
        name: Input
        description: When you configure the application input, you specify the streaming
          source,  the         in-application stream name that is created, and the
          mapping between the two
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=AddApplicationOutput:
    get:
      summary: Add Application Output
      description: Adds an external destination to your Amazon Kinesis Analytics application.
      operationId: addApplicationOutput
      x-api-path-slug: actionaddapplicationoutput-get
      parameters:
      - in: query
        name: ApplicationName
        description: Name of the application to which you want to add the output configuration
        type: string
      - in: query
        name: CurrentApplicationVersionId
        description: Version of the application to which you want add the             output
          configuration
        type: string
      - in: query
        name: Output
        description: An array of objects, each describing one output configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=AddApplicationReferenceDataSource:
    get:
      summary: Add Application Reference Data Source
      description: Adds a reference data source to an existing application.
      operationId: addApplicationReferenceDataSource
      x-api-path-slug: actionaddapplicationreferencedatasource-get
      parameters:
      - in: query
        name: ApplicationName
        description: Name of an existing application
        type: string
      - in: query
        name: CurrentApplicationVersionId
        description: Version of the application for which you are adding the reference
          data source
        type: string
      - in: query
        name: ReferenceDataSource
        description: The reference data source can be an object in your Amazon S3
          bucket
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=CreateApplication:
    get:
      summary: Create Application
      description: Creates an Amazon Kinesis Analytics application.
      operationId: createApplication
      x-api-path-slug: actioncreateapplication-get
      parameters:
      - in: query
        name: ApplicationCode
        description: One or more SQL statements that read input data, transform it,             and
          generate output
        type: string
      - in: query
        name: ApplicationDescription
        description: Summary description of the application
        type: string
      - in: query
        name: ApplicationName
        description: Name of your Amazon Kinesis Analytics application (for example,
          sample-app)
        type: string
      - in: query
        name: Inputs
        description: Use this parameter to configure the application input
        type: string
      - in: query
        name: Outputs
        description: You can configure application output to write data from any of
          the in-application streams to up to five destinations
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DeleteApplication:
    get:
      summary: Delete Application
      description: Deletes the specified application.
      operationId: deleteApplication
      x-api-path-slug: actiondeleteapplication-get
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
      - Applications
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