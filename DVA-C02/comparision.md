## Blueprint comparison 

### DVA-C01

This exam was valid until February 27, 2023.

<table><tbody><tr><td style="text-align:center;"><strong>Domain</strong></td><td style="text-align:center;"><strong>% of Exam</strong></td></tr><tr><td style="text-align:left;">Domain 1: Deployment</td><td style="text-align:center;">22%</td></tr><tr><td style="text-align:left;">Domain 2: Security</td><td style="text-align:center;">26%</td></tr><tr><td style="text-align:left;">Domain 3: Development with AWS Services</td><td style="text-align:center;">30%</td></tr><tr><td style="text-align:left;">Domain 4: Refactoring</td><td style="text-align:center;">10%</td></tr><tr><td style="text-align:left;">Domain 5: Monitoring and Troubleshooting</td><td style="text-align:center;">12%</td></tr></tbody></table>

### DVA-C02

 This exam is valid starting February 28, 2023.

<table><tbody><tr><td style="text-align:center;"><strong>Domain</strong></td><td style="text-align:center;"><strong>% of Exam</strong></td></tr><tr><td style="text-align:left;">Domain 1: Development with AWS Services</td><td style="text-align:center;">32%</td></tr><tr><td style="text-align:left;">Domain 2: Security</td><td style="text-align:center;">24%</td></tr><tr><td style="text-align:left;">Domain 3: Deployment</td><td style="text-align:center;">24%</td></tr><tr><td style="text-align:left;">Domain 4: Troubleshooting and Optimization</td><td style="text-align:center;">18%</td></tr></tbody></table>

## What is the same?

In the new version of the exam, many of the domains and tasks were reordered or renumbered; however, most of the content is the same.

## What has changed?

The C02 blueprint has been re-ordered to more logically and accurately reflect development practice. The C02 blueprint includes four domains instead of five.

The updates to the C02 exam guide distribute C01 _Domain 4 Refactoring_ across the domains for the C02 version because C01 Domain 4 had significant overlap with the other domains. The C01 Domain 4 content has not been removed from the new version of the exam but, instead, has been redistributed into the new, four-domain structure for the C02 version.

The content in these six task statements from C01 is still included in C02. However, the content has been reorganized into one or more tasks in C02:

- Content from C01 _Task Statement_ (formerly known as Objective) _1.4 Deploy serverless applications_ now appears in these C02 task statements:
    - 1.2 Develop code for AWS Lambda
    - 3.1 Prepare application artifacts to be deployed to AWS
- Content from C01 _Task Statement 2.1 Make authenticated calls to AWS services_ now appears in these C02 task statements:
    - 2.1 Implement authentication and/or authorization for applications and AWS services
    - 1.1 Develop code for applications hosted on AWS
- Content from C01 _Task Statement_ _3.1 Write code for serverless applications_ now appears in these C02 task statements:
    - 1.1 Develop code for applications hosted on AWS
    - 1.2 Develop code for AWS Lambda
    - 1.3 Use data stores in application development
- Content from C01 _Task Statement_ _3.2 Translate functional requirements into application design_ now appears in this C02 task statement:
    - 1.1 Develop code for applications hosted on AWS
- Content from C01 _Task Statement_ _3.3 Implement application design into application code_ now appears in these C02 task statements:
    - 1.1 Develop code for applications hosted on AWS
    - 1.2 Develop code for AWS Lambda
    - 4.3 Optimize applications by using AWS services and features
- Content from C01 _Task Statement 4.2_ _Migrate existing application code to run on AWS_ now appears in these C02 task statements:
    - 1.1 Develop code for applications hosted on AWS
    - 1.2 Develop code for AWS Lambda
    - 4.3 Optimize applications by using AWS services and features

One task from the C01 blueprint (1.2 Deploy applications using AWS Elastic Beanstalk) was removed. Although this task has been removed, some Elastic Beanstalk related content still will be tested within C02 Domain 1: Development with AWS Services and Domain 3: Deployment.

## What is new?

These task statements are new:

- 1.3 Use data stores in application development
- 2.3 Manage sensitive data in application code
- 3.2 Test applications in development environments
- 3.3 Automate deployment testing

### Domain 1 Task Statement 1.3 Use data stores in application development

#### **Knowledge of:**

- Amazon DynamoDB keys and indexing
- Amazon Simple Storage Service (Amazon S3) tiers and lifecycle management
- Caching strategies (for example, write-through, read-through, lazy loading, and time to live [TTL])
- Cloud storage options (for example, file, object, and databases)
- Create, read, update, and delete (CRUD) operations
- Database consistency models (for example, strongly consistent and eventually consistent)
- Differences between ephemeral and persistent data storage patterns
- Differences between query and scan operations
- High-cardinality partition keys for balanced partition access
- Relational and non-relational databases

###  **Skills in:**

- Managing data lifecycles
- Serializing and deserializing data to provide persistence to a data store
- Using data caching services
- Using, managing, and maintaining data stores

### **References:**

- [Amazon RDS Tutorials and Sample Code](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_Tutorials.html)
- [Asynchronous Invocation](https://docs.aws.amazon.com/lambda/latest/dg/invocation-async.html)
- [DynamoDB Examples Using the AWS SDK for JAVA](https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/examples-dynamodb.html)
- [Lambda Event Source Mappings](https://docs.aws.amazon.com/lambda/latest/dg/invocation-eventsourcemapping.html)
- [Managing Your Storage Lifecycle](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)
- [Read/Write Capacity Mode](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadWriteCapacityMode.html)
- [Synchronous Invocation](https://docs.aws.amazon.com/lambda/latest/dg/invocation-sync.html)
- [Using Aurora Serverless v2](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html)[What Is Amazon Aurora](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)[?  
    ](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)
- [What Is Amazon DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
- [What Is Amazon Relational Database Service (Amazon RDS)?](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

### Domain 2 Task Statement 2.3 Manage sensitive data in application code

#### **Knowledge of:**

- Data classification (for example, personally identifiable information [PII] and protected health information [PHI])
- Environment variables
- Secrets management (for example, AWS Secrets Manager and Parameter Store, a capability of AWS Systems Manager)
- Secure credential handling

#### **Skills in:**

- Encrypting environment variables that contain sensitive data
- Sanitizing sensitive data
- Using secret management services to secure sensitive data

### **References:**

- [Accessing AWS Using Your AWS Credentials](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html)
- [Amazon EBS Encryption](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSEncryption.html)
- [Amazon S3 Now Automatically Encrypts All New Objects](https://docs.aws.amazon.com/AmazonS3/latest/userguide/default-encryption-faq.html)
- [Applying the Principles of Least Privilege](https://docs.aws.amazon.com/lambda/latest/operatorguide/least-privilege.html)
- [AWS Key Management Service](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)
- [AWS Security Blog: Least Privilege](https://aws.amazon.com/blogs/security/tag/least-privilege/)
- [AWS WAF](https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html)
- [Best Practices for AWS Accounts](https://docs.aws.amazon.com/general/latest/gr/aws-access-keys-best-practices.html)
- [IAM Identities (Users, User Groups, and Roles)](https://docs.aws.amazon.com/IAM/latest/UserGuide/id.html)
- [IAM Tutorial: Delegate Access Across AWS Accounts Using IAM Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/tutorial_cross-account-with-roles.html)
- [Key Policies in AWS KMS](https://docs.aws.amazon.com/kms/latest/developerguide/key-policies.html)
- [Security in Amazon API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/security.html)
- [Security in AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/lambda-security.html)
- [What Is Amazon Cognito?](https://docs.aws.amazon.com/cognito/latest/developerguide/what-is-amazon-cognito.html)
- [What Is AWS Certificate Manager?](https://docs.aws.amazon.com/acm/latest/userguide/acm-overview.html)
- [What Is AWS CloudHSM?](https://docs.aws.amazon.com/cloudhsm/latest/userguide/introduction.html)
- [What Is AWS Secrets Manager?](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)
- [What Is IAM?](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- [What Is IAM Identity Center?](https://docs.aws.amazon.com/singlesignon/latest/userguide/what-is.html)

### Domain 3 Task Statement 3.2 Test applications in development environments 

**Knowledge of:**

- Features in AWS services that perform application deployment
- Integration testing that uses mock endpoints
- Lambda versions and aliases

**Skills in:**

- Deploying application stack updates to existing environments (for example, deploying an AWS Serverless Application Model [AWS SAM] template to a different staging environment)
- Performing mock integration for APIs and resolving integration dependencies
- Testing applications by using development endpoints (for example, configuring stages in Amazon API Gateway)
- Testing deployed code by using AWS services and tools

 **References:**

- [Build Specification Reference for CodeBuild](https://docs.aws.amazon.com/codebuild/latest/userguide/build-spec-ref.html)
- [CodeDeploy Deployments](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-steps.html) 
- [Redeploy and Roll Back a Deployment with AWS CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployments-rollback-and-redeploy.html)
- [Use the API Gateway Console to Test a REST API Method](https://docs.aws.amazon.com/apigateway/latest/developerguide/how-to-test-method.html)
- [What Is AWS CodeBuild?](https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html)
- [What Is AWS CodeCommit?](https://docs.aws.amazon.com/codecommit/latest/userguide/welcome.html)
- [What Is CodeDeploy?](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html)
- [What Is AWS CodePipeline?](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)
- [What Is AWS CodeStar?](https://docs.aws.amazon.com/codestar/latest/userguide/welcome.html)
- [Working with Commits in AWS CodeCommit Repositories](https://docs.aws.amazon.com/codecommit/latest/userguide/commits.html)
- [Working with Pull Requests in AWS CodeCommit Repositories](https://docs.aws.amazon.com/codecommit/latest/userguide/pull-requests.html)
- [Working with Repositories in AWS CodeCommit](https://docs.aws.amazon.com/codecommit/latest/userguide/repositories.html)

### Domain 3 Task Statement 3.3 Automate deployment testing

**Knowledge of:**

- API Gateway stages
- Automated software testing (for example, unit testing and mock testing)
- Branches and actions in the continuous integration and continuous delivery (CI/CD) workflow

**Skills in:**

- Creating application environments that use approved versions for integration testing (for example, Lambda aliases, container image tags, AWS Amplify branches, and AWS Copilot environments)
- Creating application test events (for example, JSON payloads for testing Lambda, API Gateway, and AWS SAM resources)
- Deploying API resources to various environments
- Implementing and deploying infrastructure as code (IaC) templates (for example, AWS SAM templates and AWS CloudFormation templates)
- Managing environments in individual AWS services (for example, differentiating between development, test, and production in API Gateway)

**References:**

- [AWS CloudFormation Stack Updates](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks.html)
- [AWS SAM Template Anatomy](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-specification-template-anatomy.html)
- [Deploy a REST API in API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/set-up-deployments.html)
- [Deploying Serverless Applications](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-deploying.html)
- [Publishing HTTP APIs for Customers to Invoke](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-publish.html)
- [What Is Amazon API Gateway?](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [What Is AWS CloudFormation?](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
- [What Is AWS OpsWorks?](https://docs.aws.amazon.com/opsworks/latest/userguide/welcome.html)
- [What Is the AWS Serverless Application Model (AWS SAM)?](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html)