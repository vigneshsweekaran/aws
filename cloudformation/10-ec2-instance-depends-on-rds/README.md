# Cloudformation template to create ec2 instance with depends on RDS creation

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack

aws cloudformation delete-stack --stack-name test-stack
```