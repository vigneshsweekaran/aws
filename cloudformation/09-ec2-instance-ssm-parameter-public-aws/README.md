# Cloudformation template to create ec2 instance with ami id from aws public ssm parameter

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack

aws cloudformation delete-stack --stack-name test-stack
```