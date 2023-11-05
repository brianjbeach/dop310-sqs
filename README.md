# re:Invent 2023 DOP310 SQS

## Better together: GitHub Actions, Amazon CodeCatalyst, or AWS CodeBuild

Learn how combining GitHub Actions with Amazon CodeCatalyst or AWS CodeBuild can maximize development efficiency. In this chalk talk, learn about the tradeoffs of using GitHub Actions runners hosted on Amazon EC2 or Amazon ECS with GitHub Actions hosted on CodeCatalyst or CodeBuild. Explore integration with other AWS services to enhance workflow automation. Join this talk to learn how GitHub Actions on AWS can take your development processes to the next level.

## Example 1 - SQS

This example uses a GitHub Action with a GitHub-hosted runner to deploy a CloudFormation Template to an AWS Account. 

## Links

* https://aws.amazon.com/blogs/security/use-iam-roles-to-connect-github-actions-to-actions-in-aws/
* https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-amazon-web-services
* https://github.com/awslabs/aws-cloudformation-templates/blob/master/aws/services/SQS/SQSStandardQueue.json
* https://github.com/aws-actions/configure-aws-credentials
* https://github.com/aws-actions/aws-cloudformation-github-deploy
