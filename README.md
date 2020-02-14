# Template for Django Docker to build through CircleCI into AWS

A quick repo to copy and pasta a django docker container. Build/Test it through CircleCI. Then deploy to AWS.

## How to configure application?

1.  Create Django Project
2.  Create ECR repository
3.  Set up CircleCI Project
4.  Configure AWS environment variables required for CircleCI
5.  Stand up ECS cluster pointing to ECR Image
