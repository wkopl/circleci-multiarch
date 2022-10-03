# circleci-multiarch

A simple demo of a circleci multi-architecture build for Graviton and x86.

The pipeline is located here:  https://app.circleci.com/pipelines/github/wkopl/circleci-multiarch?branch=main

# Example:
[![CircleCI](https://circleci.com/gh/wkopl/circleci-multiarch.svg?style=svg)](https://circleci.com/gh/wkopl/circleci-multiarch)


## Prerequisites

1.	AWS Account – To complete the steps of this blog, it will be necessary to open or have access to an AWS account. In addition, create an AWS Identity and Access Management (IAM) user with programmatic access to the account. This user account will need to have full access to the Elastic Container Registry in order to create a repository and to push the container builds into the repository.  The specific policy to attach to the IAM user is called: AmazonEC2ContainerRegistryFullAccess.  Please save the Access Key ID and the Secret Access Key.
2.	AWS CLI - Install and configure the AWS Command line Interface using the Access Key ID and Secret Access Key from Step One.
3.	GitHub Account - CircleCI connects directly to a GitHub account. In addition, there will need to be a repository in this account that contains the source code for the project, as well as the CircleCI configuration file.
4.	CircleCI Account - There are a variety of ways to create a new CircleCI account, for the sake of simplicity, connecting a GitHub account is the easiest way to create a CircleCI account. This also enables CircleCI to have access to the repositories in the account.
5.	 Fork this example code repository in GitHub into the aforementioned GitHub account.


Multiarch for the win!
