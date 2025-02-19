## Development, Messaging, and Deployment Technology and Services
  - What is CI/CD?
  - AWS Development Tools
    - CodeCommit
    - CodeBuild
    - CodeDeploy
    - CodePileline
    - Review
  - Demo： Working with AWS CloudShell and the AWS Command Line Interface （AWS CLI）
    - aws --version
    - aws s3 mb s3://jackbucket-9196657416
    - aws s3 ls
    - aws s3 cp file.txt s3://jackbucket-9196657416
    - aws s3 ls s3://jackbucket-9196657416
    - aws s3 mb help
    - CloudShell
    - CLI
    - Review
  - Demo： Using AWS Cloud9
    - browser based IDE
    - Review
  - Understanding AWS CodeArtifact
    - Central Artifact Repository
    - Review
  - Decoupling Application Components
    - Coupling
    - Tight Coupling
    - Loose Coupling
    - Microservices
      - SQS: simple queue service
      - SNS: simple notification service
      - EventBridge
    - Review
  - Introducing Amazon Simple Notification Service (SNS)
    - allows you to send or push notifications: SMS text message or email
    - A Pub-sub Model
    - A topic is an access point, allowing subscribers to receive notifications.
    - Review
  - Introducing Amazon Simple Queue Service (SQS)
    - SQS is pull-based
    - Multiple components can add and consume messages.
    - Messages are processed asynchronously.
    - Guaranteed to be processed at least once.
    - Review
  - Standard and FIFO Queues
    - Review
  - Short Polling vs Long Polling 
    - Review
  - What is Amazon simple Email Service (SES)?
    - richly formatted HTML emails vs SNS (plain text emails)
    - Review
  - Introducing Amazon EventBridge
    - EventBridge is all about event-driven architecture. An event is a change in state.
    - Events are state changes generated by services lik EC2, CloudWatch, CloudTrail.
    - Rules match events and route them to the correct target.
    - Targets respond by taking some action, like sending an SNS notification.
    - Scheduled events let us schedule an action in advance, e.g. run a process once a week or month.
    - Review
  - Understanding Step functions
    - visualize, automate, logging
    - Review
  - Deploying Infrastructure as Code with AWS CloudFormation
    - Manage, configure, and provision your AWS infrastructure as code.
    - AWS CloudFormation is an Infrastructure as Code (IaC) tool that allows you to define, provision, and manage AWS resources using templates written in YAML or JSON.
    - Review
  - What is AWS Elastic Beanstalk?
    - Deploys and scales your web applications, provisions the AWS resources for you (EC2, RDS, S3, ELB, auto scaling groups)
    - Review
  - Demo: Deploying an Application Using Elastic Beanstalk
    - load template replacing load configuration
    - Review
  - Demo: Using X-Ray to Identify Performance Issues
    - X-Ray service map provides an end-to-end view of requests as they travel through your application,
      the information can be used to troubleshoot connectivity and performance issues.
    - Review
  - Development, Messageing, and Deployment Exam Tips - Part 1
    - CI/CD
    - SNS
    - CloudShell, CLI, Cloud 9
    - CodeArtifact
    - Decouple
  - Development, Messageing, and Deployment Exam Tips - Part 2
    - SQS
    - Standard vs FIFO
    - Short Polling vs Long Polling
    - SES vs SNS
    - EventBridge
    - Step Function
    - CloudFormation
    - ElasticBeanstalk
    - X-Ray
## Migration and Transfer Technology and Services
  - Introducing the AWS Snow Family
    - Snowball 10TB
    - Snowball Edge 10TB+process
    - Snowmobile 10PB
    - Snowcone up to 14TB
    - Review 2
  - Identifying Database Migration Tools
    - AWS Database Migration Service (AWS DMS)
    - AWS Schema Conversion Tool (AWS SCT)
    - Review 2
  - Exploring the AWS Transfer Family
    - SFTP, AS2, FTPS, FTP
    - Review 2
  - AWS DataSync
  - Understanding AWS Application Discovery Service
    - Review 2
  - Introducing AWS Application Migration Service
    - Automated Lift-and-Shift
    - Review
  - Discovering AWS Migration Hub
    - Review 2
  - Migration and Transfer Exam Tips
    - Application discovery, migration, db migration
    - Review
## Artifical Intelligence, Machine Learning, and Analytics Technology and Services
  - Amazon Redshift and Redshift Serverless
    - Amazon fully managed Datawarehousing solution, designed for OLAP (Online analytical processing)
    - Review 2
  - What is Amazon Kinesis？
    - Kinesis Stream: enables you to collect, process, and analyze streaming data （data or video) in real time.
    - Review 2
  - Exploring Kinesis Data Firehose
    - Capture, transform, and load data streams into AWS data stores to enable near real-time analytics with BI tools
    - Kinesis Data Streams: capture and store streaming video and data.
    - Kinesis Data Firehose: captures, transforms, and loads data continuously into data stores.
    - Review
  - What is Amazon Athena?
    - A Service for querying data in S3
      - An interactive query service
      - Serverless， nothing to provision，pay per query/paer TB scanned
      - No need for complex ETL processes
      - Works directly with data stored on S3
      - Review 2
  - Demo: Using Athena to Query Data
    - [create table](https://github.com/pluralsight-cloud/AWS-Certified-Cloud-Practitioner-CCP-CLF-C02/tree/main/Athena_Demo)
    - Review
  - Introducing AWS Glue
    - Serverless data preparation and integration service
    - Discovers and catalogs your data
    - Performs ETL
    - prepare your data for analytics and ML
    - Review 2
  - Exploring AWS Data Exchange
    - Data Product
    - Review 2
  - Understanding Amazon Elastic Map Reduce (EMR)
    - EMR is a Big Data Platform
    - Fully managed big data solution
    - Review 2
  - What is Amazon OpenSearch？
    - Elasticsearch Service
    - Fully managed Elasticsearch Service
    - Review 2
  - Exploring Managed Streaming for Apache Kafka （Amazon MSK）
    - What is Apache Kafka？
      - widely used open-source technology
      - Build real-time data streaming pipelines
      - Process streams of events from hundreds of event sources
      - Data consumers read the data and process it in the order it was produced
    - Kinesis vs MSK both handle streaming data
    - Review 2
  - Understanding Amazon QuickSight
    - Business analytics service
    - Review 2
  - Machine Learning With Amazon SageMaker
    - A Fully Managed ML Platform
    - import and prepare your data
    - build your model
    - train your model using optimized infrastructure
    - Deploy your model
    - Review 2
  - What is Amazon Kendra?
    - An Intelligent Search Service
    - Add Custom Search: users can search based on your data
    - Query: Natural Language Processing
    - Data Source: S3, FSx, RDS, databases, GitHub, Google Drive
    - Data Types: Unstructured or semi-structured
    - Simple Fact-Based: Who, what, where?
    - Descriptive: How do I return a faulty item?
    - Review 2
  - Understanding Amazon Lex
    - Lex allows you to build conversational interfaces in your applications using natural language models.
    - Builds conversational chatbots
    - Review 2
  - Demo: Using Amazon Polly
    - Deep Learning: Add natural sounding speech to your applications
    - Review 2
  - Introducing Amazon Comprehend
    - Uses NLP to process text
    - Sentiment Analysis
    - Review 2
  - Amazon Textract, Amazon Transcribe, and Amazon Translate
    - Textract: extracts information from documents.
    - Transcribe: is a speech-to-text service.
    - Translate: is a language tranlation service.
    - Review 2
  - Demo: Using Amazon Transcribe
    - Review
  - Demo: Amazon Rekognition in Action
    - Review
  - Artificial Intelligence, Machine Learning, and Analytics Exam Tips - Part 1
    - Review
  - Artificial Intelligence, Machine Learning, and Analytics Exam Tips - Part 2