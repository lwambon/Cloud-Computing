# CLOUD COMPUTING

# Course Outline

✅Introduction to Cloud Computing  
✅Cloud Architecture and Technologies  
✅DevOps Fundamentals  
✅DevOps Tools and Techniques  
✅Automation in cloud and DevOps  
✅Advanced Topics

# Introduction to Cloud Computing

## Objectives

✅Cloud Service Models  
✅Benefits and Challenges of Cloud adoption  
✅Major Cloud Computing platforms

## What Is Cloud Computing?

Cloud Computing means storing and accessing the data and programs on remote servers that are hosted on the internet instead of the computer’s hard drive or local server.  
Cloud computing is also referred to as Internet-based computing, it is a technology where the resource is provided as a service through the Internet to the user.  
The data that is stored can be files, images, documents, or any other storable document.

## Operations that can be performed with Cloud Computing

Storage, backup, and recovery of data  
Delivery of software on demand  
Development of new applications and services  
Streaming videos and audio

## Understanding How Cloud Computing Works?

Infrastructure: Cloud computing depends on remote network servers hosted on internet for store, manage, and process the data.

On-Demand Acess: Users can access cloud services and resources based on-demand they can scale up or down the without having to invest for physical hardware.

Types of Services: Cloud computing offers various benefits such as cost saving, scalability, reliability and acessibility it reduces capital expenditures, improves efficiency.

## Evolution of cloud computing

Cloud Computing has evolved from the Distributed system to the current technology. Cloud computing has been used by all types of businesses, of different sizes and fields.

1. Distributed Systems
   In the networks, different systems are connected. When they target to send the message from different independent systems which are physically located in various places but are connected through the network. Some examples of distributed systems are Ethernet which is a LAN technology, Telecommunication network, and parallel processing. The Basic functions of the distributed systems are −

a. Resource Sharing − The Resources like data, hardware, and software can be shared between them.  
b. Open-to-all − The software is designed and can be shared.  
c. Fault Detection − The error or failure in the system is detected and can be corrected.  
Apart from the functions, the main disadvantage is that all the plan has to be in the same location and this disadvantage is overcome by the following systems −

Mainframe Computing  
Cluster Computing  
Grid Computing

1. Mainframe Computing  
   It was developed in the year 1951 and provides powerful features. Mainframe Computing is still in existence due to its ability to deal with a large amount of data. For a company that needs to access and share a vast amount of data then this computing is preferred. Among the four types of computers, mainframe computer performs very fast and lengthy computations easily.

The type of services handled by them is bulk processing of data and exchanging large-sized hardware. Apart from the performance, mainframe computing is very expensive.

2. Cluster Computing
   In Cluster Computing, the computers are connected to make it a single computing. The tasks in Cluster computing are performed concurrently by each computer also known as the nodes which are connected to the network. So the activities performed by any single node are known to all the nodes of the computing which may increase the performance, transparency, and processing speed.

To eliminate the cost, cluster computing has come into existence. We can also resize the cluster computing by removing or adding the nodes.

3. Grid Computing
   It was introduced in the year 1990. As the computing structure includes different computers or nodes, in this case, the different nodes are placed in different geographical places but are connected to the same network using the internet.

The other computing methods seen so far, it has homogeneous nodes that are located in the same place. But in this grid computing, the nodes are placed in different organizations. It minimized the problems of cluster computing but the distance between the nodes raised a new problem.

2. Web 2.0
   This computing lets the users generate their content and collaborate with other people or share the information using social media, for example, Facebook, Twitter, and Orkut. Web 2.0 is a combination of the second-generation technology World Wide Web (WWW) along with the web services and it is the computing type that is used today.

3. Virtualization
   It came into existence 40 years back and it is becoming the current technique used in IT firms. It employs a software layer over the hardware and using this it provides the customer with cloud-based services.

4. Utility Computing
   Based on the need of the user, utility computing can be used. It provides the users, company, clients or based on the business need the data storage can be taken for rent and used.

## What Are The Types of Cloud Computing Services?

Infrastructure as a Service (IaaS)  
Platform as a Service (PaaS)  
Software as a Service (SaaS)  
Function as as Service (FaaS)
Identity as Service(Ias)
Network as Service

### Infrastructure as a Service ( IaaS )

Infrastructure-as-a-Service provides access to fundamental resources such as physical machines, virtual machines, virtual storage, etc. Apart from these resources, the IaaS also offers:

Virtual machine disk storage  
Virtual local area network (VLANs)  
Load balancers  
IP addresses  
Software bundles

All of the above resources are made available to end user via server virtualization. Moreover, these resources are accessed by the customers as if they own them.

Cloud Computing IaaS

### Benefits

IaaS allows the cloud provider to freely locate the infrastructure over the Internet in a cost-effective manner. Some of the key benefits of IaaS are listed below:

Full control of the computing resources through administrative access to VMs.

Flexible and efficient renting of computer hardware.

Portability, interoperability with legacy applications.

### issues

Compatibility with legacy security vulnerabilities=>
Because IaaS offers the customer to run legacy software in provider's infrastructure, it exposes customers to all of the security vulnerabilities of such legacy software.

Virtual Machine sprawl=>The VM can become out-of-date with respect to security updates because IaaS allows the customer to operate the virtual machines in running, suspended and off state. However, the provider can automatically update such VMs, but this mechanism is hard and complex.

Robustness of VM-level isolation=>IaaS offers an isolated environment to individual customers through hypervisor. Hypervisor is a software layer that includes hardware support for virtualization to split a physical computer into multiple virtual machines.

Data erase practices=>The customer uses virtual machines that in turn use the common disk resources provided by the cloud provider. When the customer releases the resource, the cloud provider must ensure that next customer to rent the resource does not observe data residue from previous customer.

### Characteristics

Virtual machines with pre-installed software.

Virtual machines with pre-installed operating systems such as Windows, Linux, and Solaris.

On-demand availability of resources.

Allows to store copies of particular data at different locations.

The computing resources can be easily scaled up and down.

### Platform as a Service ( PaaS )

Platform-as-a-Service offers the runtime environment for applications. It also offers development and deployment tools required to develop applications. PaaS has a feature of point-and-clicktools that enables non-developers to create web applications.

App Engine of Google and Force.comare examples of PaaS offering vendors. Developer may log on to these websites and use thebuilt-in APIto create web-based applications.

### Benefits of PaaS

Lower administrative overhead
Customer need not bother about the administration because it is the responsibility of cloud provider.

Lower total cost of ownership
Customer need not purchase expensive hardware, servers, power, and data storage.

Scalable solutions
It is very easy to scale the resources up or down automatically, based on their demand.

More current system software
It is the responsibility of the cloud provider to maintain software versions and patch installations.

### Issues

Lack of portability between PaaS clouds  
Although standard languages are used, yet the implementations of platform services may vary. For example, file, queue, or hash table interfaces of one platform may differ from another, making it difficult to transfer the workloads from one platform to another.

Event based processor scheduling  
The PaaS applications are event-oriented which poses resource constraints on applications, i.e., they have to answer a request in a given interval of time.

Security engineering of PaaS applications  
Since PaaS applications are dependent on network, they must explicitly use cryptography and manage security exposures.

### Characteristics

PaaS offers browser based development environment. It allows the developer to create database and edit the application code either via Application Programming Interface or point-and-click tools.

PaaS provides built-in security, scalability,and web service interfaces.

PaaS provides built-in tools for definingworkflow, approval processes, and business rules.

It is easy to integrate PaaS with other applications on the same platform.

PaaS also provides web services interfaces that allow us to connect the applications outside the platform.

### PaaS Types

Stand-alone development environments
Thestand-alone PaaSworks as an independent entity for a specific function. It does not include licensing or technical dependencies on specific SaaS applications.

Application delivery-only environments
The application delivery PaaS includes on-demand scalingandapplication security.

Open platform as a service
Open PaaS offers an open source software that helps a PaaS provider to run applications.

Add-on development facilities
The add-on PaaS allows to customize the existing SaaS platform.

### SaaS (software as a service)

Software-as a-Service (SaaS) model allows to provide software application as a service to the end users. It refers to a software that is deployed on a host service and is accessible via Internet. There are several SaaS applications listed below:

Billing and invoicing system  
Customer Relationship Management (CRM) applications  
Help desk applications  
Human Resource (HR) solutions  
Some of the SaaS applications are not customizable such as Microsoft Office Suite. But SaaS provides us Application Programming Interface (API), which allows the developer to develop a customized application.

### Characteristics

SaaS makes the software available over the Internet.

The software applications are maintained by the vendor.

The license to the software may be subscription based or usage based. And it is billed on recurring basis.

SaaS applications are cost-effective since they do not require any maintenance at end user side.

They are available on demand.

They can be scaled up or down on demand.

They are automatically upgraded and updated.

SaaS offers shared data model. Therefore, multiple users can share single instance of infrastructure. It is not required to hard code the functionality for individual users.

All users run the same version of the software.

### Benefits

1. Modest software tools

The SaaS application deployment requires a little or no client side software installation, which results in the following benefits:

No requirement for complex software packages at client side  
Little or no risk of configuration at client side
Low distribution cost

2. Efficient use of software licenses  
   The customer can have single license for multiple computers running at different locations which reduces the licensing cost. Also, there is no requirement for license servers because the software runs in the provider's infrastructure.

3. Centralized management and data

The cloud provider stores data centrally. However, the cloud providers may store data in a decentralized manner for the sake of redundancy and reliability.

4. Platform responsibilities managed by providers

All platform responsibilities such as backups, system maintenance, security, hardware refresh, power management, etc. are performed by the cloud provider. The customer does not need to bother about them.

5. Multitenant solutions

Multitenant solutions allow multiple users to share single instance of different resources in virtual isolation. Customers can customize their application without affecting the core functionality.

### Issues

1. Browser based risks

If the customer visits malicious website and browser becomes infected, the subsequent access to SaaS application might compromise the customer's data.

To avoid such risks, the customer can use multiple browsers and dedicate a specific browser to access SaaS applications or can use virtual desktop while accessing the SaaS applications.

2. Network dependence

The SaaS application can be delivered only when network is continuously available. Also network should be reliable but the network reliability cannot be guaranteed either by cloud provider or by the customer.

3. Lack of portability between SaaS clouds

Transferring workloads from one SaaS cloud to another is not so easy because work flow, business logics, user interfaces, support scripts can be provider specific.

## Open SaaS and SOA

Open SaaS uses those SaaS applications, which are developed using open source programming language. These SaaS applications can run on any open source operating system and database. Open SaaS has several benefits listed below:

No License Required
Low Deployment Cost
Less Vendor Lock-in
More portable applications
More Robust Solution.

## Identity as a Service

Identity refers to set of attributes associated with something to make it recognizable. All objects may have same attributes, but their identities cannot be the same. A unique identity is assigned through unique identification attribute.

There are several identity services that are deployed to validate services such as validating web sites, transactions, transaction participants, client, etc. Identity-as-a-Service may include the following:

Directory services  
Federated services  
Registration  
Authentication services  
Risk and event monitoring  
Single sign-on services  
Identity and profile management

### Benefits

Increased site conversation rates  
Access to greater user profile content  
Fewer problems with lost passwords  
Ease of content integration into social networking sites

## Network as a Service

Network-as-a-Serviceallows us to access to network infrastructure directly and securely. NaaS makes it possible to deploycustom routing protocols.

NaaS uses virtualized network infrastructureto provide network services to the customer. It is the responsibility of NaaS provider to maintain and manage the network resources. Having a provider working for a customer decreases the workload of the customer. Moreover, NaaS offers network as a utility. NaaS is also based on pay-per-use model.

### Benefits

Independence -->Each customer is independent and can segregate the network.

Bursting-->The customer pays for high-capacity network only on requirement.

Resilience-->The reliability treatments are available, which can be applied for critical applications.

Analytics-->The data protection solutions are available, which can be applied for highly sensitive applications.

Ease of Adding New Service Elements-->It is very easy to integrate new service elements to the network.

Support Models-->A number of support models are available to reduce operation cost.

Isolation of Customer Traffic-->The customer traffic is logically isolated.

## What Are Cloud Deployment Models?

The following are the Cloud Deployment Models:

1. Public Deployment model
2. Private deployment model
3. Hybrid deployment model

### Private Deployment Model

Private Cloud allows systems and services to be accessible within an organization. The Private Cloud is operated only within a single organization. However, it may be managed internally by the organization itself or by third-party.

### Advantages

1. High Security and Privacy-
   Private cloud operations are not available to general public and resources are shared from distinct pool of resources. Therefore, it ensures highsecurityandprivacy.

2. More Control-
   The private cloud has more control on its resources and hardware than public cloud because it is accessed only within an organization.

3. Cost and Energy Efficiency
   The private cloud resources are not as cost effective as resources in public clouds but they offer more efficiency than public cloud resources.

### Disadvantages

1. Restricted Area of Operation-
   The private cloud is only accessible locally and is very difficult to deploy globally.

2. High Priced-
   Purchasing new hardware in order to fulfill the demand is a costly transaction.

3. Limited Scalability-
   The private cloud can be scaled only within capacity of internal hosted resources.

4. Additional Skills-
   In order to maintain cloud deployment, organization requires skilled expertise.

### Public Deployment Model

Public Cloudallows systems and services to be easily accessible to general public. The IT giants such as Google, Amazon and Microsoftoffer cloud services via Internet.

### Advantages

1. Cost Effective-
   Since public cloud shares same resources with large number of customers it turns out inexpensive.

2. Reliability-
   The public cloud employs large number of resources from different locations. If any of the resources fails, public cloud can employ another one.

3. Flexibility-
   The public cloud can smoothly integrate with private cloud, which gives customers a flexible approach.

4. Location Independence-
   Public cloud services are delivered through Internet, ensuring location independence.

5. Utility Style Costing-
   Public cloud is also based on pay-per-use model and resources are accessible whenever customer needs them.

6. High Scalability-
   Cloud resources are made available on demand from a pool of resources, i.e., they can be scaled up or down according the requirement.

### Disadvantages

1. Low Security- In public cloud model,data is hosted off-site and resources are shared publicly, therefore does not ensure higher level of security.

2. Less Customizable-It is comparatively less customizable than private cloud.

### Hybrid Deployment Model

Hybrid Cloudis a mixture ofpublicandprivatecloud. Non-critical activities are performed using public cloud while the critical activities are performed using private cloud.

### Advantages

1. Scalability-
   It offers features of both, the public cloud scalability and the private cloud scalability.

2. Flexibility-
   It offers secure resources and scalable public resources.

3. Cost Efficiency-
   Public clouds are more cost effective than private ones. Therefore, hybrid clouds can be cost saving.

4. Security-
   The private cloud in hybrid cloud ensures higher degree of security.

### Disadvantages

1. Networking Issues-
   Networking becomes complex due to presence of private and public cloud.

2. Security Compliance-
   It is necessary to ensure that cloud services are compliant with security policies of the organization.

3. Infrastructure Dependency-
   The hybrid cloud modelis dependent on internal IT infrastructure, therefore it is necessary to ensure redundancy across data centers.

## Characteristics Of Cloud Computing

1. Scalability: With Cloud hosting, it is easy to grow and shrink the number and size of servers based on the need. This is done by either increasing or decreasing the resources in the cloud.

2. Save Money: An advantage of cloud computing is the reduction in hardware costs. Instead of purchasing in-house equipment, hardware needs are left to the vendor.

3. Reliability: If one server goes offline it will have no effect on availability, as the virtual servers will continue to pull resources from the remaining network of servers.

4. Physical Security: The underlying physical servers are still housed within data centers and so benefit from the security measures that those facilities implement to prevent people from accessing or disrupting them on-site.

5. Outsource Management: When you are managing the business, Someone else manages your computing infrastructure.

## Top Reasons to Switch from On-premise to Cloud Computing

The following are the Top reasons to switch from on-premise to cloud computing:

1. Reduces cost: The cost-cutting ability of businesses that utilize cloud computing over time is one of the main advantages of this technology.By the use of cloud servers businesses will save and reduce costs with no need to employ a staff of technical support personnel to address server issues.

2. More storage: For software and applications to execute as quickly and efficiently as possible, it provides more servers, storage space, and computing power. Many tools are available for cloud storage such as Dropbox, Onedrive, Google Drive, iCloud Drive, etc.

3. Employees Better Work Life Balance: Direct connections between cloud computing benefits, and the work and personal lives of an enterprise’s workers can both improve because of cloud computing.

## Top leading Cloud Computing companies

1. Amazon Web Services(AWS)

One of the most successful cloud-based businesses is Amazon Web Services(AWS), which is an Infrastructure as a Service(Iaas) offering that pays rent for virtual computers on Amazon’s infrastructure.

2. Microsoft Azure Cloud Platform

Microsoft is creating the Azure platform which enables the .NET Framework Application to run over the internet as an alternative platform for Microsoft developers. This is the classic Platform as a Service(PaaS).

3. Google Cloud Platform ( GCP )

Google has built a worldwide network of data centers to service its search engine. From this service, Google has captured the world’s advertising revenue. By using that revenue, Google offers free software to users based on infrastructure. This is called Software as a Service(SaaS).

## Advantages of Cloud Computing

1. Cost Efficiency: Cloud Computing provides flexible pricing to the users with the principal pay-as-you-go model. It helps in lessening capital expenditures of Infrastructure, particularly for small and medium-sized businesses companies.

2. Flexibility and Scalability: Cloud services facilitate the scaling of resources based on demand. It ensures the efficiency of businesses in handling various workloads without the need for large amounts of investments in hardware during the periods of low demand.

3. Collaboration and Accessibility: Cloud computing provides easy access to data and applications from anywhere over the internet. This encourages collaborative team participation from different locations through shared documents and projects in real-time resulting in quality and productive outputs.

4. Automatic Maintenance and Updates: AWS Cloud takes care of the infrastructure management and keeping with the latest software automatically making updates they is new versions.

## Disadvantages Of Cloud Computing

1. Security Concerns: Storing of sensitive data on external servers raised more security concerns which is one of the main drawbacks of cloud computing.

2. Downtime and Reliability: Even though cloud services are usually dependable, they may also have unexpected interruptions and downtimes. These might be raised because of server problems, Network issues or maintenance disruptions in Cloud providers which negative effect on business operations, creating issues for users accessing their apps.

3. Dependency on Internet Connectivity: Cloud computing services heavily rely on Internet connectivity. For accessing the cloud resources the users should have a stable and high-speed internet connection for accessing and using cloud resources. In regions with limited internet connectivity, users may face challenges in accessing their data and applications.

4. Cost Management Complexity: The main benefit of cloud services is their pricing model that coming with Pay as you go but it also leads to cost management complexities. On without proper careful monitoring and utilization of resources optimization, Organizations may end up with unexpected costs as per their use scale.

## Cloud Sustainability

Enery Efficiency: Cloud Providers supports the optimization of data center operations for minimizing energy consumption and improve efficiency.

Renewable Energy: On increasing the adoption of renewable energy sources like solar and wind power to data centers and reduce carbon emissions.

Virtualization: Server virtualization facilitates better utilization of hardware resources, reducing the need for physical servers and lowering the energy consumptions.

## Use Cases Of Cloud Computing

1. Scalable Infrastructure: Infrastructure as a Service (IaaS) enables organizations to scale computing resources based on demand without investing in physical hardware.

2. Efficient Application Development: Platform as a Service (PaaS) simplifies application development, offering tools and environments for building, deploying, and managing applications.

3. Streamlined Software Access: Software as a Service (SaaS) provides subscription-based access to software applications over the internet, reducing the need for local installation and maintenance.

4. Data Analytics: Cloud-based platforms facilitate big data analytics, allowing organizations to process and derive insights from large datasets efficiently.

5. Disaster Recovery: Cloud-based disaster recovery solutions offer cost-effective data replication and backup, ensuring quick recovery in case of system failures or disasters.
