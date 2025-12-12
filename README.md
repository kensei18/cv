# CV

English / [Japanese](./README_JA.md)

### SAKAI, Kensei

Github: https://github.com/kensei18

LinkedIn: https://www.linkedin.com/in/kensei-sakai/

Languages: Japanese (native) / English (B2)

## Technologies

##### Language / Framework

Go / TypeScript(Express.js, React, Vue.js) / Ruby(Ruby on Rails) / Python(FastAPI) / HTML / CSS

##### Database

MySQL / MongoDB / PostgreSQL / DynamoDB

##### Network Interface

gRPC (Protocol Buffers) / GraphQL / REST

##### Virtualization Technology

Docker / lima

##### Cloud Provider

AWS (EC2, S3, DocumentDB, CloudFront, ECR, ECS, Athena, SQS, SES, Lambda, DynamoDB, Route53, CloudFormation, CloudWatchLogs, API Gateway, StepFunctions) / GCP (Firebase, Cloud Run, Cloud Build, CloudSQL, Cloud Storage, Cloud PubSub, Cloud Logging, Big Query)

##### Version Management

Github / Gitlab

##### CI/CD

Github Actions / CircleCI / Gitlab CI

##### Others

Terraform / Algolia / Datadog / Ory (Kratos, Hydra, Oathkeeper)

## Work History

### TIER IV, Inc. (2023.12 - Present) - Software Engineer

TIER IV is a Japanese startup developing autonomous driving systems and is known for releasing the open-source autonomous driving software "Autoware". The company provides "Web.Auto", a system for supporting autonomous driving on the web (including Fleet Management System, CI/CD, data infrastructure, machine learning infrastructure, remote monitoring, etc.).[[1]](#__1) [[2]](#__2)

As a member of the Auth team, I am responsible for developing foundational microservices used across Web.Auto, including authentication, authorization, contract management, usage measurement, and notification systems.

#### Performance Improvement of Web.Auto's Authorization Infrastructure

To achieve an authorization mechanism that can withstand large-scale scaling of Web.Auto in the future, I reviewed the token issuance mechanism and implemented performance improvements.

##### Technologies

Go, Python, TypeScript, k6, Datadog

##### Responsibilities

- Requirement definition
- Bottleneck identification
- Consideration and implementation of performance improvement measures
- Measurement of performance improvement effects

#### Development of Usage Measurement Microservice for Web.Auto Applications

Developed a new microservice to measure customer usage of various applications provided by Web.Auto, TIER IV's autonomous driving support system.

##### Technologies

Go, Python, TypeScript, AWS (Lambda, DynamoDB, ECS, Route53, SQS, SES, CloudFormation, CloudWatchLogs, API Gateway), Datadog, Slack API

##### Responsibilities

- Domain design
- Microservice implementation
- Leading the development team
- Leading communication with other teams utilizing the microservice

#### Development of Notification Microservice for Web.Auto Applications

Developed a new notification microservice allowing various applications in Web.Auto to send notifications to customers through different channels.

##### Technologies

Go, AWS (Lambda, DynamoDB, Route53, SQS, CloudFormation, CloudWatchLogs, API Gateway, StepFunctions), Datadog

##### Responsibilities

- Non-functional requirements definition
- System design
- Domain design
- Microservice implementation
- Leading the development team
- Leading communication with other teams utilizing the microservice
- Release
- Maintenance and operation

#### Operation of Authentication, Authorization, and Contract Management Microservices for Web.Auto

Responsible for the operation of authentication, authorization, and contract management microservices used in Web.Auto.

##### Technologies

Go, PostgreSQL, AWS (Lambda, DynamoDB, ECS, Route53, SQS, CloudFormation, CloudWatchLogs, API Gateway), Ory (Kratos, Hydra, Oathkeeper)

##### Responsibilities

- Monitoring and on-call response
- Handling inquiries and consultations from other teams regarding authentication, authorization, and contracts
- Feature additions and performance improvements

### Money Forward, Inc. (2021.09 - 2023.11) - Software Engineer

#### Internal Application for Online Factoring Service with Apollo Server & Next.js

Develop an internal application for Biz Forward Inc., a subsidiary company that operates a bilateral online factoring business, to enable internal users to manage cases and payments.

##### Technologies

TypeScript(Node.js, Next.js), Go, GCP(Cloud Run, Firebase, CloudSQL, Cloud Storage, Cloud PubSub, Cloud Logging, Big Query), GraphQL(Apollo), Terraform, Docker, Sentry

##### Responsibilities

- Requirement definition, overall design, database design, implementation, release, infrastructure configuration, maintenance and operation of new features
- Refactoring and additional testing for existing features
- Maintenance of server logs

#### Microservices development for an accounting application built in Ruby on Rails

Microservices development project to decouple journal data from a monolithic accounting application built in Ruby on Rails

##### Technologies

Ruby on Rails, Go, MySQL, Docker, gRPC

##### Responsibilities

- Development of gRPC client to call microservices functions in Ruby on Rails
- Development of dedicated regression testing tools
- Implementation, test design, and testing for switching to microservices
- Development of microservices with Golang
- Development and operation of development environment infrastructure for Mac with Docker and lima

### Spacely, Inc. (2020.06 - 2021.09) - Software Engineer

#### Furniture placement features in VR spaces

Development of new features that allows users to freely coordinate rooms in VR spaces by automatically or manually placing furniture, appliances, etc. that are actually sold

##### Technologies

Python, FastAPI, A-Frame, Vue.js, Ruby on Rails, MongoDB, MySQL, AWS(EC2, S3, DocumentDB, CloudFront, ECR, ECS, SQS), Github Actions, Docker, Algolia

##### Responsibilities

- Design, development, and operation of VR space and furniture placement features in A-Frame and Vue.js
- Design, development, and operation of a furniture information backend service using FastAPI and MongoDB
- Design and implementation of access control for 3D files placed in S3
- Implementation and operation of asynchronous communication with image processing applications using SQS
- Investigation and improvement of FastAPI application performance
- Migration of features and data from FastAPI + MongoDB furniture information backend service to Algolia

#### Real estate property management application with VR

Maintenance, modification and development of VR real estate property management application composed of Ruby on Rails, Vue.js and React

##### Technologies

Ruby on Rails, JavaScript, Vue.js, jQuery, MySQL, AWS(EC2, S3)

##### Responsibilities

- Refactoring and adding tests to Ruby on Rails application
- Replacement of frontend SPA from React to Vue.js
- Performance improvement of Ruby on Rails application
- Modification of Company HP

### Sony Corporation (2018.04 - 2019.12) - Management and Financial Accounting

#### Management Accounting - Broadcasting Equipment Business

Management accounting and supply chain management for four business categories in the Broadcast Equipment business

##### Responsibilities

- Reporting monthly results and forecast PL
- Forecasting product lifetime profit
- Production and sales management
- Mid-term plan and annual budget creation
- Adjustment of transaction prices with each production site and sales company

#### Financial Accounting - Smartphone Business

Processing and management of receivables and payables of smartphone business

##### Responsibilities

- Processing of monthly financial statements
- Computerization of invoices for overseas company-owned factories

## Education

- The University of Tokyo, Faculty of Education, Division of Physical and Health Education
  - 2012.04 - 2018.03

## Other Activities

- Development of surgical medical education support application
  - Go, TypeScript, React, PostgreSQL, GraphQL, Docker, GCP(Firebase / Cloud Run / Cloud SQL / Cloud Build)
  - Established company
  - Obtained international patents
- Software Engineering Fundamentals
  - 2020.01 - 2020.06
