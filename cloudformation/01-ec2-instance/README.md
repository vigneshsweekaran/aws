# Cloudformation template to create EC2 instance

# Commands
```
aws cloudformation deploy --template-file template.yaml --stack-name ec2-instance

aws cloudformation delete-stack --stack-name ec2-instance
```

**Cloudformation template creates the following**
* Ec2 instance
* Security Group
* ElasticIP

** Template
* Resource - Ec2 instance, Security group, ElasticIp
* Parameters - Choose Instance type, Enable/disable ElasticIP
* Mappings - To get the AMI Id dynamically based on region 
