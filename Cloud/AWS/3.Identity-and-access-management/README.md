# AWS Identity and Access Management

## Basics
- **IAM** :  web service that enables you to manage access to your AWS account and resources.
  - **AWS IAM User** : An IAM user represents a person or service that interacts with AWS. 
  - **AWS IAM Policy** : To manage access and provide permissions to AWS services and resources, you create IAM policies and attach them to IAM users, groups, and roles.
  - **AWS IAM Groups** : An IAM group is a collection of users.
  - **AWS IAM Roles** : When you assume a role, IAM dynamically provides temporary credentials that expire after a defined period of time, between 15 minutes and 36 hours.
## Nice to remember
- Having a service in diffrent services(like EC2 and S3), do not allowed to be access without authentication and authorization even if they lived in the same account.
- Everything in AWS is Api call.
- Policy can not assign to root user, it has to assign to IAM user.
- IAM supports MFA.
- 

## Resources
- [IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
- [IAM Best Practices](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)