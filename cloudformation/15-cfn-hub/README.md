# Cloudformation template to create EC2 instance with cfn hub

cfn init will install the script only when a new instance is created. After that if we update the stack, and instance is not replaced, that time, the script changes will be updated by cfn-hub

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack

aws cloudformation delete-stack --stack-name test-stack
```

