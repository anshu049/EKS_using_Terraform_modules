# Inside terraform.tfvars we can define

`vpc_cidr_block             = "10.0.0.0/16"`

`private_subnet_cidr_blocks = ["10.0.1.0/24", "10.0.2.0/24", "10.0.3.0/24"]`

`public_subnet_cidr_blocks  = ["10.0.4.0/24", "10.0.5.0/24", "10.0.6.0/24"]`

# policy for EKS nodegroup
(https://github.com/kubernetes/autoscaler/blob/master/cluster-autoscaler/cloudprovider/aws/README.md)

# Metric server
(https://github.com/kubernetes-sigs/metrics-server)

`kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml`
