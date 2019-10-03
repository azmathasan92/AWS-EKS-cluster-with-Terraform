# Spin-up EKS cluster With Terraform
Complete practical to setup amazon eks cluster using terraform

# Amazon Elastic Kubernetes Service (EKS): Fully managed Kubernetes control plane
Amazon EKS is a managed service that makes it easy for you to use Kubernetes on AWS without needing to install and operate your own Kubernetes control plane. Amazon Elastic Kubernetes Service (Amazon EKS) makes it easy to deploy, manage, and scale containerized applications using Kubernetes on AWS.

Amazon EKS runs the Kubernetes management infrastructure for you across multiple AWS availability zones to eliminate a single point of failure. Amazon EKS is certified Kubernetes conformant so you can use existing tooling and plugins from partners and the Kubernetes community. Applications running on any standard Kubernetes environment are fully compatible and can be easily migrated to Amazon EKS.


![alt text](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwiLz4eeq__kAhVKvo8KHfAnCs0QjRx6BAgBEAQ&url=https%3A%2F%2Faws.amazon.com%2Feks%2F&psig=AOvVaw2tAHTAKIQgP3xdtwH8_Gs6&ust=1570166235221679)




prerequisite:
1. terraform -> link: https://www.terraform.io/downloads.html
2. aws-cli -> link: https://docs.aws.amazon.com/cli/latest/userguide/install-linux-al2017.html
3. aws-iam-authenticator -> link: https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html

Steps:
1. Clone this repo
2. cd to the repo root directory
3. terraform init
4. terraform apply
