# Cloudformation template to create lambda from from s3 bucket and bucket is versioned

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack --capabilities CAPABILITY_NAMED_IAM

aws cloudformation delete-stack --stack-name test-stack
```