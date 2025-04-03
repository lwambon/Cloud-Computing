# AUTOMATION IN CLOUD AND DEVOPS

# Objectives

✅Automating infrastructure provisioning(Infrastructure as Code)  
✅Automated testing and deployment  
✅Scaling and optimizing cloud resources

## Automation in Cloud and DevOps

## Introduction

Automation is a critical aspect of Cloud Computing and DevOps, enabling organizations to provision infrastructure, deploy applications, test software, and scale resources with minimal manual intervention.

By leveraging automation, teams can:  
✅ Reduce human errors  
✅ Speed up deployments  
✅ Improve security and compliance  
✅ Optimize resource usage

This document covers three key areas of automation in cloud and DevOps:

. Infrastructure as Code (IaC) for provisioning infrastructure

. Automated testing and deployment in CI/CD pipelines

. Scaling and optimizing cloud resources

## Automating Infrastructure Provisioning (Infrastructure as Code - IaC)

### What is Infrastructure as Code (IaC)?

Infrastructure as Code (IaC) is the practice of managing and provisioning infrastructure (servers, databases, networking, etc.) using machine-readable configuration files instead of manual processes.

Benefits of IaC  
✅ Consistency – Eliminates configuration drift  
✅ Scalability – Deploy multiple environments quickly  
✅ Version Control – Uses Git for tracking infrastructure changes  
✅ Efficiency – Reduces manual provisioning efforts

Popular IaC Tools

1. Terraform  
   Terraform is an open-source IaC tool that allows declarative provisioning of cloud infrastructure across AWS, Azure, and Google Cloud.

✅ Uses HCL (HashiCorp Configuration Language)
✅ Supports multi-cloud environments
✅ Works with Docker, Kubernetes, and CI/CD pipelines

Example Terraform Script (AWS EC2 Instance)

```hcl
provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "web_server" {
  ami           = "ami-12345678"
  instance_type = "t2.micro"
}
```

This script automates the creation of an AWS EC2 instance.

2. AWS CloudFormation
   CloudFormation is Amazon's native IaC tool that automates AWS infrastructure deployment.

✅ Uses YAML or JSON templates
✅ Manages stacks of AWS resources
✅ Supports rollback in case of failures

Example CloudFormation Template

```yaml
Resources:
  MyInstance:
    Type: AWS::EC2::Instance
    Properties:
      InstanceType: t2.micro
      ImageId: ami-12345678
```

This template provisions an EC2 instance on AWS.

3. Ansible
   Ansible is an agentless automation tool that helps manage infrastructure using YAML playbooks.

✅ Best for configuring servers
✅ Works with SSH (Linux) and WinRM (Windows)
✅ Automates application deployments

Example Ansible Playbook

```yaml
- name: Install Apache
  hosts: web_servers
  tasks:
    - name: Install Apache
      apt:
        name: apache2
        state: latest
```

This playbook installs Apache Web Server on remote servers.

## Automated Testing and Deployment

### Why Automate Testing & Deployment?

🚀 Automated Testing ensures software quality by running pre-defined test cases.  
🚀 Automated Deployment reduces downtime and human errors.

CI/CD Pipelines for Automated Testing & Deployment
CI/CD (Continuous Integration/Continuous Deployment) automates:  
✅ Building applications  
✅ Testing code changes  
✅ Deploying to production

Popular CI/CD Tools

1. Jenkins  
   Jenkins is an open-source automation server used for CI/CD pipelines.

✅ Supports automated builds, tests, and deployments
✅ Integrates with Git, Docker, Kubernetes, and AWS
✅ Uses Jenkinsfile for pipeline scripting

Example Jenkins Pipeline Script

```groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'scp target/*.jar user@server:/deploy'
            }
        }
    }
}
```

This pipeline builds, tests, and deploys a Java application.

2. GitHub Actions
   GitHub Actions automates testing and deployment directly from GitHub repositories.

✅ Uses YAML workflows
✅ Integrates with Docker, Kubernetes, AWS, and Google Cloud

Example GitHub Actions Workflow

```yaml
name: CI Pipeline
on: push
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Build Application
        run: mvn clean install
```

This workflow builds a Java application when code is pushed to GitHub.

3. GitLab CI/CD
   GitLab has a built-in CI/CD tool for automating testing and deployment.

✅ Uses .gitlab-ci.yml for pipeline configuration
✅ Supports Docker, Kubernetes, and cloud deployment

Example GitLab CI/CD Pipeline

```yaml
stages:
  - build
  - test
  - deploy

build:
  stage: build
  script:
    - mvn clean install

test:
  stage: test
  script:
    - mvn test

deploy:
  stage: deploy
  script:
    - scp target/*.jar user@server:/deploy
```

This pipeline automates the software development lifecycle.

## Scaling and Optimizing Cloud Resources

### Why Scale Cloud Resources?

✅ Ensures high availability  
✅ Handles traffic spikes  
✅ Optimizes cost & performance

Types of Scaling in Cloud

1. Vertical Scaling (Scaling Up) – Increasing the size of existing instances (e.g., upgrading from t2.micro to t2.large).
2. Horizontal Scaling (Scaling Out) – Adding more instances (e.g., increasing web servers from 2 to 10).

Cloud Auto-Scaling Tools  
AWS Auto Scaling  
 Automatically adjusts EC2 instances based on demand.  
 Reduces costs by stopping unused instances.  
 Works with Elastic Load Balancer (ELB).

Example AWS Auto Scaling Policy

```json
{
  "AutoScalingGroupName": "my-auto-scaling-group",
  "ScalingPolicies": [
    {
      "AdjustmentType": "ChangeInCapacity",
      "ScalingAdjustment": 2
    }
  ]
}
```

This doubles the number of instances when demand increases.

Kubernetes Horizontal Pod Autoscaler (HPA)  
 Automatically scales Kubernetes pods based on CPU usage.

Example Kubernetes HPA Command

```sh
kubectl autoscale deployment my-app --cpu-percent=50 --min=1 --max=10
```

This scales pods between 1 and 10 based on CPU utilization.

Conclusion
Automation in Cloud and DevOps improves efficiency, security, and scalability.

Infrastructure as Code (IaC) tools like Terraform, Ansible, and CloudFormation automate infrastructure setup.

CI/CD Pipelines with Jenkins, GitHub Actions, and GitLab streamline software delivery.

Cloud Scaling using AWS Auto Scaling and Kubernetes HPA optimizes resources.

By mastering these tools, DevOps teams can accelerate deployments, reduce costs, and improve system reliability.

## References

📌 Terraform Documentation – https://developer.hashicorp.com/terraform/docs  
📌 Ansible Documentation – https://docs.ansible.com  
📌 Jenkins Documentation – https://www.jenkins.io/doc/  
📌 AWS Auto Scaling Docs – https://docs.aws.amazon.com/autoscaling/  
📌 Kubernetes HPA Docs – https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/
