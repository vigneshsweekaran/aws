# Cloudformation template to create lambda from s3 bucket

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack --capabilities CAPABILITY_NAMED_IAM

aws cloudformation delete-stack --stack-name test-stack
```