# Cloudformation template to create two security group amd protect one security group not to update

Using stack policy we can restrict the update on resources created by cloudformation 

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name test-stack

aws cloudformation delete-stack --stack-name test-stack
```
