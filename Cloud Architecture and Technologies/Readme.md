# CLOUD ARCHITECTURE AND TECHNOLOGIES

# Objectives

✅Virtualization and Containerization(Docker, Kubernetes)  
✅Microservices and serverless computing  
✅Cloud Security and Compliances

## What is Virtualization In Cloud Computing?

Virtualization is a technique, which allows to share single physical instance of an application or resource among multiple organizations or tenants (customers). It does so by assigning a logical name to a physical resource and providing a pointer to that physical resource on demand.

### Virtualization Concept

Creating a virtual machine over existing operating system and hardware is referred as Hardware Virtualization. Virtual Machines provide an environment that is logically separated from the underlying hardware.

The machine on which the virtual machine is created is known as host machine and virtual machine is referred as a guest machine. This virtual machine is managed by a software or firmware, which is known as hypervisor.

### Hypervisor

The hypervisor is a firmware or low-level program that acts as a Virtual Machine Manager. There are two types of hypervisor:

1. Type 1 hypervisor executes on bare system.LynxSecure, RTS Hypervisor, Oracle VM, Sun xVM Server, Virtual Logic VLXare examples of Type 1 hypervisor.

Type1 Hypervisor
The type1 hypervisordoes not have any host operating system because they are installed on a bare system.

2. Type 2 hypervisor is a software interface that emulates the devices with which a system normally interacts.Containers, KVM, Microsoft Hyper V, VMWare Fusion, Virtual Server 2005 R2, Windows Virtual PCandVMWare workstation 6.0are examples of Type 2 hypervisor.

### Types of Hardware Virtualization

Here are the three types of hardware virtualization:

1. Full Virtualization
2. Emulation Virtualization
3. Paravirtualization

### Full Virtualization

In full virtualization, the underlying hardware is completely simulated. Guest software does not require any modification to run.

### Emulation Virtualization

In Emulation, the virtual machine simulates the hardware and hence becomes independent of it. In this, the guest operating system does not require modification.

### Paravirtualization

In Paravirtualization, the hardware is not simulated. The guest software run their own isolated domains.

Cloud Computing Paravirtualization
VMware vSphere is highly developed infrastructure that offers a management infrastructure framework for virtualization. It virtualizes the system, storage and networking hardware.

## What is Containerization?

Containerization is a type of virtualization in which all the components of an application are bundled into a single container image and can be run in isolated user space on the same shared operating system.

Containers are lightweight, portable, and highly conducive to automation. As a result, containerization has become a cornerstone of development pipelines and application infrastructure for a variety of use cases.

### The Layers of Containerization

1. Hardware infrastructure: With any application, it all starts with physical compute resources somewhere. Whether those resources are your own laptop or spread across multiple cloud datacenters, they are a must-have for containers to work.
2. Host operating system: The next layer that sits atop the hardware layer is the host operating system. As with the hardware layer, this could be as simple as the Windows or \*nix operating system running on your own computer or abstracted away completely by a cloud service provider.
3. Container engine: This is where things start to get interesting. Container engines run on top of your host operating system and virtualize resources for containerized apps. The simplest example of this layer is running Docker on your own computer.
4. Containerized apps: Containerized apps are units of code that include all the libraries, binaries, and configuration an application requires to run.

### The Benefits of Containerization

1. Portability: Containerization solves this problem because the same exact container images — which include dependencies — can be run everywhere.
2. Speed: Containers tend to start up in a fraction of the time virtual machines or bare metal servers take. While specific boot times will vary depending on resources and the size of an app, generally speaking containers start up in seconds while virtual machines can take minutes.
3. Efficiency: Because containers only include what an app needs to run, they are significantly more lightweight than virtual machines.
4. Simplicity of deployment: Because containers are portable and lightweight, they can easily be deployed almost anywhere.
5. Scalability: Containerized applications start up quickly, don’t take up too much space, and are easy to deploy. As a result, containerization makes it much easier to scale your deployments. This is why containers have become a cornerstone of microservices and cloud-based applications.

### Specific Containerization Use Cases

1. Microservices: A microservices architecture is built around the idea of many small, independent, and loosely coupled services working together. Because containers are a great way to deploy isolated units of code, they have become the de-facto standard for deploying microservices.
2. CI/CD: Continuous integration/continuous deployment (CI/CD) is all about testing and deploying reliable software fast. By bundling applications into portable, lightweight, and uniform units of code, containerization enables better CI/CD because containers are automation friendly, reduce dependency issues, and minimize resource consumption.
3. Modernizing legacy apps: Many teams are moving legacy monolithic applications to the cloud. However, in order to do so, they need to be sure the app will actually run in the cloud. In many cases, this means leveraging containerization to ensure the app can be deployed anywhere.

## Kubernetes and Containers

Kubernetes, also known as K8s, is a popular tool to help scale and manage container deployments. Containerization software like Docker or LXC lacks the functionality to orchestrate larger container deployments, and K8s fills that gap

### What exactly can Kubernetes do?

1. Rollouts and rollbacks: K8s allows you to automate the creation and deployment of new containers or removal of existing containers in a container cluster based on predefined rules around resource utilization.
2. Storage mounting: With Kubernetes, you can automatically mount storage resources for your containers.
3. Resource allocation: Balancing CPU and RAM consumption at scale is a challenging task. K8s enables you to define CPU and RAM requirements and then it automatically handles optimal deployment of your containers within the constraints of your resources (nodes).
4. Self-healing: With K8s, you can define health checks and if your containers do not meet the requirements, they will be automatically restored or replaced.
5. Configuration management: K8s helps securely manage container configurations including sensitive data such as tokens and SSH keys.
6. Load balancing: Kubernetes can automatically perform load balancing across multiple containers to enable efficient performance and resource utilSecuring containers.

## Dockers

Docker is a software platform that allows you to build, test, and deploy applications quickly. Docker packages software into standardized units called containers that have everything the software needs to run including libraries, system tools, code, and runtime. Using Docker, you can quickly deploy and scale applications into any environment and know your code will run.

Running Docker on AWS provides developers and admins a highly reliable, low-cost way to build, ship, and run distributed applications at any scale.

## Microservices and serverless computing

Microservices: A microservices architecture is built around the idea of many small, independent, and loosely coupled services working together. Because containers are a great way to deploy isolated units of code, they have become the de-facto standard for deploying microservices.  
Serverless computing is a cloud computing execution model that allocates machine resources on an as-used basis. Under a serverless model, developers can build and run applications without having to manage any servers and pay only for the exact amount of resources used. Instead, the cloud service provider is responsible for provisioning, managing, and scaling the cloud infrastructure that runs the application code

## Architecture Of Cloud Computing

Cloud computing architecture refers to the components and sub-components required for cloud computing. These components typically refer to:

Front end ( Fat client, Thin client)
Back-end platforms ( Servers, Storage )
Cloud-based delivery and a network ( Internet, Intranet, Intercloud )

### Front End ( User Interaction Enhancement )

The User Interface of Cloud Computing consists of 2 sections of clients. The Thin clients are the ones that use web browsers facilitating portable and lightweight accessibilities and others are known as Fat Clients that use many functionalities for offering a strong user experience.

### Back-end Platforms ( Cloud Computing Engine )

The core of cloud computing is made at back-end platforms with several servers for storage and processing computing. Management of Applications logic is managed through servers and effective data handling is provided by storage. The combination of these platforms at the backend offers the processing power, and capacity to manage and store data behind the cloud.

### Cloud-Based Delivery and Network

On-demand access to the computer and resources is provided over the Internet, Intranet, and Intercloud. The Internet comes with global accessibility, the Intranet helps in internal communications of the services within the organization and the Intercloud enables interoperability across various cloud services. This dynamic network connectivity ensures an essential component of cloud computing architecture on guaranteeing easy access and data transfer.

## Cloud Security

Cloud security recommended to measures and practices designed to protect data, applications, and infrastructure in cloud computing environments. The following are some of the best practices of cloud security:

1. Data Encryption: Encryption is essential for securing data stored in the cloud. It ensures that data remains unreadable to unauthorized users even if it is intercepted.
2. Access Control: Implementing strict access controls and authentication mechanisms helps ensure that only authorized users can access sensitive data and resources in the cloud.
3. Multi-Factor Authentication (MFA): MFA adds an extra layer of security by requiring users to provide multiple forms of verification, such as passwords, biometrics, or security tokens, before gaining access to cloud services.
