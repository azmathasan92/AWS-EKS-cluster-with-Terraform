# Spin-up EKS cluster With Terraform
Complete practical to setup amazon eks cluster using terraform

# Amazon Elastic Kubernetes Service (EKS): Fully managed Kubernetes control plane
Amazon EKS is a managed service that makes it easy for you to use Kubernetes on AWS without needing to install and operate your own Kubernetes control plane. Amazon Elastic Kubernetes Service (Amazon EKS) makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS.

Amazon EKS runs the Kubernetes management infrastructure for you across multiple AWS availability zones to eliminate a single point of failure. Amazon EKS is certified Kubernetes conformant so you can use existing tooling and plugins from partners and the Kubernetes community. Applications running on any standard Kubernetes environment are fully compatible and can be easily migrated to Amazon EKS.

![EKS](https://d1.awsstatic.com/diagrams/product-page-diagrams/product-page-diagram-AmazonEKS-v2.dd41321fd3aa0915b93396c13e739351d2160ba8.png)

# prerequisite:
1. terraform -> Download link: https://www.terraform.io/downloads.html
2. aws-cli -> Download link: https://docs.aws.amazon.com/cli/latest/userguide/install-linux-al2017.html
3. aws-iam-authenticator -> Download link: https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html

# Steps:
1. Clone this repo
2. cd to the repo root directory
3. run terraform init command
4. run terraform apply command

After the above procedure you will see output of the kubeconfig and configmap

you have the create the kubeconfig file and config map from the output. Finally you have to create the configmap which you have created from the output

kubectl --kubeconfig kubeconfig create -f configmap.yml

