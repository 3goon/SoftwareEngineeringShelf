# AWS Security

## Definations
- **Model** : AWS created the shared responsibility model. One part is on AWS and another part is on Customer . This distinction of responsibility is commonly referred to as security of the cloud, versus security in the cloud.
    - __AWS Reponsibility__ : AWS is responsible for security of the cloud.
    - __Customer Responsibility__ : Customer is responsible for security in the cloud. 
- **Authentication** :When you create your AWS account, you use a combination of an email address and a password to verify your identity. If the user types in the correct email and password, the system assumes the user is allowed to enter and grants them access. This is the process of authentication.
- **Authorization** : Authorization is the process of giving users permission to access AWS resources and services. 
- **Root User** : Can do anything on the AWS account and should be protected.
  - **How to protected Root User** 
    - Create Strong password
    - Never share username and password or access keys.
    - Use MFA (Multi-Factor Authentication)
    - Do not use root user for day to day tasks.
- **Access Keys** : Access keys allow you to make programmatic requests from the AWS CLI or AWS API.
    - Access Keys consists of two parts : **access key**, **secret access key**
  
## Nice to remember
- For MFA we could use __Virtual MFA__ on mobile devices.
- Virtual MFA works with : Authy, Duo Mobile, LastPass Authenticator, Microsoft Authenticator, Google Authenticator

## Resources
- [Virtual MFA](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html)
- [Supported MFA Devices](https://aws.amazon.com/iam/features/mfa/)
- [List of root user tasks](https://docs.aws.amazon.com/general/latest/gr/root-vs-iam.html#aws_tasks-that-require-root)