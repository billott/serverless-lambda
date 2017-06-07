=========
CHANGELOG
=========

1.0.0
=====
* Initial release on Github.
* Introduces Cognito User Pools for authentication along with newer looking UI.
* Adds API Gateway IAM Authorization
* Provides support for workshop to run in all regions that are currently supporting Lambda and API Gateway services.
* Introduces multi-region stack support for workshop to run in any of the 5 existing regions that have API Gateway and Lambda.
* Solves hardcoded attribute dependencies, allowing for multiple stacks to run simultaneously in the same AWS account. Resources are created with stack name prepended to the resource names.
* Removes caching from API Gateway stage to reduce costs for long running stacks.
* Provides baseline chat application via CloudFormation stack, Lambda functions, DynamoDB tables, and API Gateway resources.