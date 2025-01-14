# Awesome CloudOps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

IT operations are at the heart of every organization.

These days, it is no longer a matter of moving or not to the Cloud, but how fast you can run, secure, oversee, and control something into the Cloud.

How can you transform your organization with **agility**, **speed**, and **automation** WHILE MAINTAINING **security**, **compliance**, and **spending management**?

Cloud Operations provides a secure and efficient way to operate in the Cloud through models and tools.

What are the most used ones to daily manage IT Operations in the Cloud?


# Index

- [Tools](#tools)
- [Resources](#resources)
  - [Podcasts](#podcasts)
  - [Guides and Tutorials](#guides-and-tutorials)
    - [API](#apis)
    - [NoSQL Databases](#nosql-databases)
    - [Security](#security)


## Mantained by

- **[Noovolari](https://github.com/Noovolari)**

## Tools

| Name  | Repository | Cloud Providers | Category | Description |
| ----- | ---------- | --------------- | -------- | ----------- |
| [AWS Cloud Development Kit](https://docs.aws.amazon.com/cdk/v2/guide/home.html) | [<img align="right" src="https://img.shields.io/github/stars/aws/aws-cdk?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/aws/aws-cdk" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/aws/aws-cdk">](https://github.com/aws/aws-cdk) | <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"> | IaC, AWS, AWS CloudFormation | An Infrastructure as Code framework that allows DevOps to define a Cloud infrastructure in code, by applying programming practices like unit tests and code reviews. It allows to use both low and gith level constructs that can be re-used in other projects.|
| [AWS Deployment Framework](https://github.com/awslabs/aws-deployment-framework)  | [<img align="right" src="https://img.shields.io/github/stars/awslabs/aws-deployment-framework?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/awslabs/aws-deployment-framework" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/awslabs/aws-deployment-framework">](https://github.com/awslabs/aws-deployment-framework)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"> | governance, cloud-environment, cloud-provider-tool | An extensive and flexible framework by AWS to manage and deploy resources across multiple AWS accounts and regions within an AWS Organization.|
| [AWS IAM Authenticator for Kubernetes](https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html)  | [<img align="right" src="https://img.shields.io/github/stars/kubernetes-sigs/aws-iam-authenticator?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/hashicorp/terraform" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/kubernetes-sigs/aws-iam-authenticator">](https://github.com/kubernetes-sigs/aws-iam-authenticator)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"><br> <img align="right" src="https://img.shields.io/badge/-kubernetes-blue" alt="Kubernetes"> | AWS, Kubernetes, AWS IAM, AWS Security Token Service | A tool that enables the kubectl CLI  to authenticate to an Amazon Elastic Kubernetes Service cluster using AWS IAM credentials associated with identities such as users and roles. |
| [Configure AWS Credentials](https://github.com/aws-actions/configure-aws-credentials)  | [<img align="right" src="https://img.shields.io/github/stars/aws-actions/configure-aws-credentials?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/aws-actions/configure-aws-credentials" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/aws-actions/configure-aws-credentials">](https://github.com/aws-actions/configure-aws-credentials)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"> | GitHub Action, AWS, AWS Credentials | Configure AWS credential environment variables for use in other GitHub Actions.|
| [Leapp](https://www.leapp.cloud)  | [<img align="right" src="https://img.shields.io/github/stars/noovolari/leapp?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/noovolari/leapp" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/noovolari/leapp">](https://github.com/noovolari/leapp)| <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"><br> <img align="right" src="https://img.shields.io/badge/-azure-blue" alt="Azure">                                                                                                                        | IAM, Security | Desktop App for developers to manage, secure, and access the Cloud. |
| [Lens](https://k8slens.dev/)  | [<img align="right" src="https://img.shields.io/github/stars/lensapp/lens?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/lensapp/lens" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/lensapp/lens">](https://github.com/lensapp/lens)| <img align="right" src="https://img.shields.io/badge/-kubernetes-blue" alt="Kubernetes">                                                                                                                        | Container, DesktopApp, Kubernetes | Desktop App to run Kubernetes locally|
| [K6](https://k6.io/)  | [<img align="right" src="https://img.shields.io/github/stars/grafana/k6?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/grafana/k6" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/grafana/k6">](https://github.com/grafana/k6)| | APIs, Load-testing |  Load testing tool for developers and testers|
| [Pulumi](https://www.pulumi.com/)  | [<img align="right" src="https://img.shields.io/github/stars/pulumi/pulumi?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/pulumi/pulumi" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/pulumi/pulumi">](https://github.com/pulumi/pulumi)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"><br><img align="right" src="https://img.shields.io/badge/-kubernetes-blue" alt="Kubernetes"><img align="right" src="https://img.shields.io/badge/-azure-blue" alt="Azure"><img align="right" src="https://img.shields.io/badge/-gcp-green" alt="GCP">  | IaC, cloud-environment, cloud-provider-tool | A universal Infrastructure as Code SDK that enables you to create, deploy, and manage infrastructure on any cloud, using your favorite languages.|
| [Skyplane](https://skyplane.org)  | [<img align="right" src="https://img.shields.io/github/stars/skyplane-project/skyplane?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/turbot/steampipe" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/skyplane-project/skyplane">](https://github.com/skyplane-project/skyplane)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"><br> <img align="right" src="https://img.shields.io/badge/-azure-blue" alt="Azure"> <br> <img align="right" src="https://img.shields.io/badge/-gcp-green" alt="GCP"> <br> | data-transfer | bulk data transfers between any cloud 🔥|
| [Steampipe](https://steampipe.io/)  | [<img align="right" src="https://img.shields.io/github/stars/turbot/steampipe?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/turbot/steampipe" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/turbot/steampipe">](https://github.com/turbot/steampipe)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"><br> <img align="right" src="https://img.shields.io/badge/-azure-blue" alt="Azure"> <br> <img align="right" src="https://img.shields.io/badge/-gcp-green" alt="GCP"> <br> <img align="right" src="https://img.shields.io/badge/-alibaba-orange" alt="Alibaba"> | query, mySQL, cloud-finder | Use SQL to query cloud infrastructure, SaaS, code, logs, and more.|
| [Terraform](https://www.terraform.io/)  | [<img align="right" src="https://img.shields.io/github/stars/hashicorp/terraform?label=%E2%AD%90%EF%B8%8F&logo=github" alt="Stars"><br><img align="right" src="https://img.shields.io/github/issues-raw/hashicorp/terraform" alt="Issues"><br><img align="right" src="https://img.shields.io/github/last-commit/hashicorp/terraform">](https://github.com/hashicorp/terraform)|  <img align="right" src="https://img.shields.io/badge/-aws-orange" alt="AWS"><br> <img align="right" src="https://img.shields.io/badge/-azure-blue" alt="Azure"> <br> <img align="right" src="https://img.shields.io/badge/-gcp-green" alt="GCP"> <br> <img align="right" src="https://img.shields.io/badge/-alibaba-orange" alt="Alibaba"> | IaC, multicloud | Safely and predictably create, change, and improve infrastructure codifying APIs into declarative configuration files.|


## Resources

### Guides and Tutorials

#### APIs
- **Load testing your APIs with k6 - [part 1](https://www.brunodasilvalenga.com/blog/load-testing-your-apis-how-to-make-sure-youre-ready-part-1) - [part 2](https://www.brunodasilvalenga.com/blog/load-testing-your-apis-how-to-make-sure-youre-ready-part-2)**

#### NoSQL Databases
- [Guide to DynamoDB ranging from basic to advanced concepts](https://www.dynamodbguide.com/)

#### Security
- [Guide of security and hacking in AWS](https://hackingthe.cloud/)


### Podcasts

| Name  | Host | Platform | Description |
| ----- | ---- | -------- | ----------- | 
| [Cloud Automation Weekly](https://podcast.taimos.de/) | [Thorsten Hoeger](https://www.linkedin.com/in/hoegertn) | [<img src="https://img.shields.io/badge/-spotify-brightgreen">](https://open.spotify.com/show/7J3rTmvAES6brOiMrdGfUk) <br> [<img src="https://img.shields.io/badge/-apple podcast-purple">](https://podcasts.apple.com/us/podcast/cloud-automation-weekly/id1644082147?uo=4) <br> [<img src="https://img.shields.io/badge/-google podcast-yellow">](https://podcasts.google.com/feed/aHR0cHM6Ly9mZWVkcy50cmFuc2lzdG9yLmZtL2Nsb3VkLWF1dG9tYXRpb24td2Vla2x5) | Discover new ways to improve your AWS infrastructure by automating everything. |


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
