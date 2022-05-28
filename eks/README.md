# AWS EKS

### Create EKS cluster with Fargate
```
eksctl create cluster --name my-cluster --region us-west-2 --fargate
```

##### To configure credentials to connect to eks using kubectl
```
aws eks update-kubeconfig --name my-cluster
```