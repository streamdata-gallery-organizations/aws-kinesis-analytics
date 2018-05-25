---
name: AWS Kinesis Analytics
x-slug: aws-kinesis-analytics
description: Amazon Kinesis Analytics is the easiest way to process streaming data
  in real time with standard SQL without having to learn new programming languages
  or processing frameworks. Amazon Kinesis Analytics enables you to create and run
  SQL queries on streaming data so that you can gain actionable insights and respond
  to your business and customer needs promptly.Amazon Kinesis Analytics takes care
  of everything required to run your queries continuously and scales automatically
  to match the volume and throughput rate of your incoming data. With Amazon Kinesis
  Analytics, you only pay for the resources your queries consume. There is no minimum
  fee or setup cost.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Kinesis Analytics
created: "2018-05-24"
modified: "2018-05-24"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Kinesis Analytics API Add Application Input
  x-api-slug: aws-kinesis-analytics-api
  description: Adds a streaming source to your Amazon Kinesis application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=AddApplicationInput
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionaddapplicationinput-get-openapi.md
- name: AWS Kinesis Analytics API Add Application Output
  x-api-slug: aws-kinesis-analytics-api
  description: Adds an external destination to your Amazon Kinesis Analytics application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=AddApplicationOutput
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionaddapplicationoutput-get-openapi.md
- name: AWS Kinesis Analytics API Add Application Reference Data Source
  x-api-slug: aws-kinesis-analytics-api
  description: Adds a reference data source to an existing application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=AddApplicationReferenceDataSource
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionaddapplicationreferencedatasource-get-openapi.md
- name: AWS Kinesis Analytics API Create Application
  x-api-slug: aws-kinesis-analytics-api
  description: Creates an Amazon Kinesis Analytics application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=CreateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actioncreateapplication-get-openapi.md
- name: AWS Kinesis Analytics API Delete Application
  x-api-slug: aws-kinesis-analytics-api
  description: Deletes the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=DeleteApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actiondeleteapplication-get-openapi.md
- name: AWS Kinesis Analytics API Delete Application Output
  x-api-slug: aws-kinesis-analytics-api
  description: Deletes output destination configuration from your application configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=DeleteApplicationOutput
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actiondeleteapplicationoutput-get-openapi.md
- name: AWS Kinesis Analytics API Delete Application Reference Data Source
  x-api-slug: aws-kinesis-analytics-api
  description: Deletes a reference data source configuration from the specified application
    configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=DeleteApplicationReferenceDataSource
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actiondeleteapplicationreferencedatasource-get-openapi.md
- name: AWS Kinesis Analytics API Describe Application
  x-api-slug: aws-kinesis-analytics-api
  description: Returns information about a specific Amazon Kinesis Analytics application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=DescribeApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actiondescribeapplication-get-openapi.md
- name: AWS Kinesis Analytics API Discover Input Schema
  x-api-slug: aws-kinesis-analytics-api
  description: Infers a schema by evaluating sample records on the specified streaming
    source (Amazon Kinesis stream or Amazon Kinesis Firehose delivery stream).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=DiscoverInputSchema
  tags: Schema
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actiondiscoverinputschema-get-openapi.md
- name: AWS Kinesis Analytics API List Applications
  x-api-slug: aws-kinesis-analytics-api
  description: Returns a list of Amazon Kinesis Analytics applications in your account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=ListApplications
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionlistapplications-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionlistapplications-get-openapi.md
- name: AWS Kinesis Analytics API Start Application
  x-api-slug: aws-kinesis-analytics-api
  description: Starts the specified Amazon Kinesis Analytics application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=StartApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionstartapplication-get-openapi.md
- name: AWS Kinesis Analytics API Stop Application
  x-api-slug: aws-kinesis-analytics-api
  description: Stops the application from processing input data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=StopApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionstopapplication-get-openapi.md
- name: AWS Kinesis Analytics API Update Application
  x-api-slug: aws-kinesis-analytics-api
  description: Updates an existing Amazon Kinesis Analytics application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: ://///?Action=UpdateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/actionupdateapplication-get-openapi.md
- name: AWS Kinesis Analytics API
  x-api-slug: aws-kinesis-analytics-api
  description: Amazon Kinesis Analytics is the easiest way to process streaming data
    in real time with standard SQL without having to learn new programming languages
    or processing frameworks. Amazon Kinesis Analytics enables you to create and run
    SQL queries on streaming data so that you can gain actionable insights and respond
    to your business and customer needs promptly.Amazon Kinesis Analytics takes care
    of everything required to run your queries continuously and scales automatically
    to match the volume and throughput rate of your incoming data. With Amazon Kinesis
    Analytics, you only pay for the resources your queries consume. There is no minimum
    fee or setup cost.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AmazonKinesis_AmazonKinesisAnalytics.png
  humanURL: https://aws.amazon.com/kinesis/analytics/
  baseURL: :///
  tags: AWS Kinesis Analytics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-kinesis-analytics/master/_listings/aws-kinesis-analytics/openapi.md
x-common:
- type: x-authentication
  url: https://docs.aws.amazon.com/kinesisanalytics/latest/dev/authentication-and-access-control.html
- type: x-best-practices
  url: https://docs.aws.amazon.com/kinesisanalytics/latest/dev/best-practices.html
- type: x-console
  url: https://console.aws.amazon.com/kinesisanalytics/home
- type: x-documentation
  url: https://docs.aws.amazon.com/kinesisanalytics/latest/dev/API_Reference.html
- type: x-faq
  url: https://aws.amazon.com/kinesis/analytics/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/kinesis/analytics/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/kinesis/analytics/pricing/
- type: x-website
  url: https://aws.amazon.com/kinesis/analytics/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---