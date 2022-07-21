# Cloudformation template to create custom resource using lambda to delete all keys in the s3 bucket

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack

aws cloudformation delete-stack --stack-name test-stack
```