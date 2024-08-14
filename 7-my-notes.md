# AZ-900: Microsoft Azure Fundamentals

These items are relevant to the AZ-900: Microsoft Azure Fundamentals certification, as they cover fundamental concepts and features of Microsoft Azure. Understanding these topics is important for anyone seeking to gain a foundational understanding of Azure and its capabilities.

## Key Concepts

### Azure Resource Groups
A resource group is a logical container that holds related resources for an application or solution. It helps in organizing and managing resources such as virtual machines, storage accounts, and networking components.

### WebJobs
WebJobs is a feature in Azure that allows you to run background tasks or scheduled jobs alongside your web application. It provides a way to run scripts or executables in the context of an Azure App Service.

### Sovereign Regions
Sovereign regions in Azure refer to specific geographic regions that are dedicated to serving specific government or regulatory requirements. These regions are designed to meet the data residency, compliance, and sovereignty needs of customers in specific countries or regions.

### Security Groups
Security groups in Azure are used to manage network security by controlling inbound and outbound traffic to Azure resources. They allow you to define network security rules that determine which traffic is allowed or denied based on source and destination IP addresses, ports, and protocols.

### Azure Policy
Azure Policy is a service in Azure that allows you to enforce and govern compliance with organizational standards and best practices. It helps you ensure that your Azure resources are deployed and configured correctly.

### PowerShell and Cmdlets
PowerShell is a scripting language and command-line shell that is widely used for automation and management tasks in Azure. Azure provides a set of cmdlets (pronounced "command-lets") that allow you to interact with Azure resources using PowerShell.

### Azure Blueprints
Azure Blueprints is a service that helps you define and deploy a repeatable set of Azure resources that adhere to organizational standards, patterns, and compliance requirements. It allows you to create and manage templates for resource deployment.

#### Key Features of Azure Blueprints
- **Role-Based Access Control (RBAC)**: Define and enforce access control policies for Azure resources.
- **Policy Definitions**: Integrate with Azure Policy Definitions to enforce compliance and governance policies.
- **ARM Templates**: Leverage Azure Resource Manager (ARM) Templates to define the infrastructure and configuration of Azure resources.

### Azure Resource Manager
Azure Resource Manager (ARM) is the deployment and management service for Azure. It provides a consistent management layer that enables you to create, update, and delete resources in your Azure account.

### Azure Reservations
Azure Reservations offer discounts on Azure services and workloads by committing to one-year or three-year plans.

### Azure Advisor
Azure Advisor provides guidance and recommendations to improve security, performance, and high availability in an Azure environment.

## Financial Models

### Capital Expenditure (CapEx) vs Operational Expenditure (OpEx)

#### Capital Expenditure (CapEx)
- **Definition**: Upfront costs incurred by an organization to acquire, upgrade, and maintain physical assets.
- **Characteristics**:
  - High Initial Cost
  - Depreciation over the useful life of the asset
  - Ownership and maintenance responsibility
- **Examples**: Purchasing servers, data centers, networking equipment.

#### Operational Expenditure (OpEx)
- **Definition**: Ongoing costs for running day-to-day operations.
- **Characteristics**:
  - Pay-as-You-Go
  - Flexibility to scale up or down
  - No Depreciation
- **Examples**: Subscription to cloud services, software licenses, utility bills.

### Comparison in the Context of Cloud Computing
- **CapEx**: Traditional IT infrastructure with significant upfront investment and long-term commitment.
- **OpEx**: Cloud computing with pay-as-you-go model, scalability, and maintenance handled by the cloud provider.

## Service Models

### Infrastructure as a Service (IaaS)
- **Definition**: Provides virtualized computing resources over the internet.
- **Characteristics**:
  - Virtual Machines
  - Scalable Storage
  - Networking Capabilities
  - User Control over OS and Applications
- **Examples in Azure**:
  - Azure Virtual Machines
  - Azure Storage
  - Azure Virtual Network

### Platform as a Service (PaaS)
- **Definition**: Provides a platform for developing, running, and managing applications without dealing with the underlying infrastructure.
- **Characteristics**:
  - Development Tools
  - Managed Services
  - Scalability
  - Focus on Development
- **Examples in Azure**:
  - Azure App Services
  - Azure SQL Database
  - Azure Functions
  - Azure Firewall
  - Azure Kubernetes Service (AKS)

### Software as a Service (SaaS)
- **Definition**: Provides software applications over the internet on a subscription basis.
- **Characteristics**:
  - Subscription-Based
  - Managed by Provider
  - Accessibility from any device
- **Examples in Azure**:
  - Microsoft 365
  - Dynamics 365
  - Azure DevOps

## Security and Compliance

### Microsoft Defender for Cloud
Can be used to apply security policies which can ensure compliance with security standards.

### Azure Trust Center
Provides customers and partners with easier access to regulatory compliance information. Trust Center is accessible through the Service Trust Portal.

### Microsoft Trust Portal
Contains trust documents covering security implementation and design documentation about how Microsoft keeps customer data secure, including:
- Audit reports
- Data protection white papers, FAQs, penetration tests, and risk assessment tools
- Azure stack security and compliance solutions and support

### Windows Hello for Business

**Windows Hello for Business** is a security feature in Windows 10 and Windows 11 that replaces traditional passwords with strong two-factor authentication on devices. It leverages biometrics (such as facial recognition or fingerprint scanning) or a PIN to authenticate users, providing a more secure and user-friendly authentication method.

#### Key Features

1. **Passwordless Authentication**
   - **Biometrics**: Uses facial recognition or fingerprint scanning to authenticate users.
   - **PIN**: Allows users to authenticate using a PIN that is tied to the specific device.

2. **Multi-Factor Authentication**
   - Combines something you know (PIN), something you have (device), and something you are (biometrics) to provide a robust authentication mechanism.

3. **Device-Based Authentication**
   - The authentication credentials are tied to the device, making it more secure as the credentials cannot be used on another device.

4. **Support for Multiple Account Types**
   - **Microsoft Account**: Personal accounts used for services like Outlook, OneDrive, and Xbox Live.
   - **Active Directory Account**: Corporate accounts used within an organization's network.
   - **Azure AD Account**: Accounts used for accessing Azure services and Office 365.
   - **Identity Provider Accounts**: Supports accounts from identity providers that comply with Fast ID Online (FIDO) v2.0 authentication standards.

5. **Enhanced Security**
   - **Asymmetric Key Pair**: Uses public and private key pairs for authentication, where the private key is stored securely on the device.
   - **Anti-Spoofing**: Includes anti-spoofing measures to ensure that biometric data cannot be easily faked.

6. **User Convenience**
   - **Fast Login**: Provides a quick and seamless login experience.
   - **Single Sign-On (SSO)**: Allows users to access multiple applications and services without needing to re-enter credentials.

#### Benefits

1. **Improved Security**
   - Reduces the risk of phishing attacks and password theft.
   - Ensures that authentication credentials are stored securely on the device.

2. **User-Friendly**
   - Simplifies the login process with biometrics or a PIN.
   - Eliminates the need to remember complex passwords.

3. **Compliance**
   - Helps organizations meet regulatory requirements for strong authentication.

4. **Flexibility**
   - Supports a wide range of account types and authentication methods.

By leveraging Windows Hello for Business, organizations can enhance their security posture while providing a more convenient and efficient authentication experience for their users.

## Azure Services

### Azure DNS
A portfolio of products that extends on-premises environments to the cloud and can include many Azure services and capabilities, such as data centers, edge locations, and remote offices.

### Azure Firewall
Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources. It is a fully stateful firewall as a service with built-in high availability and unrestricted cloud scalability. Azure Firewall provides comprehensive security features to control and monitor your network traffic.

#### Key Features
- **Stateful Firewall**
- **Traffic Filtering**: Allows you to create, enforce, and log application and network connectivity policies across subscriptions and virtual networks.
- **Network Rules**: Supports both inbound and outbound filtering rules based on IP addresses, ports, and protocols.
- **Threat Intelligence-Based Filtering**: Integrates with Microsoft Threat Intelligence to alert and deny traffic from/to known malicious IP addresses and domains.

### Azure Kubernetes Services (AKS)
A PaaS offering in Azure - Azure Kubernetes Service (AKS) is a managed container orchestration service provided by Microsoft Azure that simplifies the deployment, management, and operations of Kubernetes clusters. AKS is designed to handle the complexities of Kubernetes, allowing developers and IT administrators to focus on building and running applications rather than managing the underlying infrastructure.

#### Key Features
- **Managed Kubernetes**
- **Simplified Cluster Management**: AKS handles the provisioning, upgrading, and scaling of Kubernetes clusters, reducing the operational overhead.
- **Automatic Updates**: Ensures that the Kubernetes control plane is always up-to-date with the latest security patches and features.

### VPN Gateway vs ExpressRoute or VNet Peering
#### VPN Gateway
- **Connectivity**: Uses the public internet to create a secure, encrypted connection between your on-premises network and Azure.
- **Use Case**: Suitable for scenarios where cost is a concern and the performance requirements are moderate.
- **Performance**: Generally lower performance and higher latency compared to ExpressRoute.
- **Security**: Provides encryption for data in transit.
- **Cost**: Typically lower cost compared to ExpressRoute.

#### ExpressRoute
- **Connectivity** Provides a private connection between your on-premises network and Azure, bypassing the public internet.
- **Use Case**: Ideal for scenarios requiring high performance, low latency, and higher security.
- **Performance**: Offers higher bandwidth options and more consistent network performance.
- **Security**: More secure as it does not traverse the public internet.
- **Cost**: Higher cost due to dedicated private connection.
#### VNet Peering
- **Connectivity**: Enables direct, private IP connectivity between two Azure Virtual Networks (VNets) within the same region or across regions.
- **Use Case**: Suitable for connecting VNets within Azure, either within the same region or across different regions.
- **Performance**: High performance with low latency as it uses the Azure backbone network.
- **Security**: Traffic between peered VNets is private and does not traverse the public internet.
- **Cost**:Generally lower cost compared to VPN Gateway and ExpressRoute for VNet-to-VNet connectivity.
#### Summary
- **VPN Gateway**: Best for secure, cost-effective connections over the public internet with moderate performance needs.
- **ExpressRoute**: Best for high-performance, low-latency, and secure private connections, suitable for enterprise-grade applications.
- **VNet Peering**: Best for high-performance, low-latency connections between Azure VNets, ideal for intra-Azure network connectivity.

### Azure Blob Storage Use Cases
- Serving images or documents directly to a browser
- Storing files for distributed access
- Streaming video and audio
- Writing to log files

### Service Failure Notifications
Can be viewed from Azure Monitor. Pertinent to virtual machines, resource health events can represent one of four health statuses:
- Available
- Unavailable
- Degraded
- Unknown

### Azure Cost Management Solution
Provides tools to monitor, allocate, and optimize cloud spending.

### Data Transfer Costs
Inbound data transfers (data going into Azure data centers) are free. Outbound data transfers are subject to charges.


## Azure Storage Services
### Azure Storage Services

Azure Storage offers a variety of services to meet different storage needs. Below are the primary storage services available on the Azure platform:

#### Blob Storage
Purpose: Optimized for storing massive amounts of unstructured data, such as text or binary data.

Use Cases: Storing files, backups, logs, and media files.

Features:
- Tiers: Hot, Cool, and Archive tiers for cost-effective storage.
- Access: Supports REST-based object storage.
- Integration: Works with Azure Data Lake Storage for big data analytics.

#### File Storage
Purpose: Provides fully managed file shares in the cloud that are accessible via the SMB protocol.

Use Cases: Lift-and-shift applications, shared storage for applications, and replacing or supplementing on-premises file servers.

Features:
- Protocol Support: Supports SMB 3.0 and SMB 2.1.
- Access Control: Integration with Azure Active Directory (Azure AD) for access control.
- Data Protection: Snapshot support for data protection.

#### Queue Storage
Purpose: Designed for storing large numbers of messages that can be accessed from anywhere via authenticated calls.

Use Cases: Decoupling application components, load leveling, and asynchronous processing.

Features:
- Message Delivery: Supports FIFO (First In, First Out) message delivery.
- Message Size: Messages can be up to 64 KB in size.
- Integration: Works with Azure Functions for serverless processing.

#### Table Storage
Purpose: Provides a NoSQL key-value store for rapid development using semi-structured datasets.

Use Cases: Storing structured, non-relational data, such as user data for web applications, device information, and metadata.

Features:
- Querying: Supports OData protocol for querying.
- Scalability: Scalable to handle large amounts of data.
- Cost-Effective: Suitable for large datasets.

#### Disk Storage
Purpose: Provides persistent, high-performance disk storage for Azure Virtual Machines.

Use Cases: Running enterprise applications, databases, and high-performance workloads.

Features:
- Options: Managed and unmanaged disk options.
- Performance: SSD and HDD options for different performance needs.
- Data Protection: Integration with Azure Backup and Azure Site Recovery for data protection and disaster recovery.

### Summary
Azure Storage offers a comprehensive set of storage solutions to meet various needs, from unstructured data storage to high-performance disk storage for virtual machines. Each storage service is designed to provide scalability, security, and cost-effectiveness for different use cases.
- **Azure Blob** – Object store for text and binary data.
- **Azure Disks** – Block-level storage volumes.
- **Azure Table** – Structured NoSQL data in the cloud.
- **Azure Files** – Shard access that utilizes Server Message Block (SMB) protocol.

## Azure Monitor and Log Analytics Tool
### Azure Monitor

Azure Monitor is a comprehensive service in Azure designed to provide performance and availability monitoring for applications and services across various environments, including Azure, other cloud platforms, and on-premises infrastructure. It collects data from multiple sources into a unified data platform, enabling detailed analysis for trends and anomalies.

#### Key Features

- Data Collection: Gathers data from Azure resources, on-premises environments, and other cloud platforms.
- Analysis: Analyzes collected data to identify trends and detect anomalies.
- Alerts: Provides rich features to quickly identify and respond to critical situations affecting your applications.
- Metrics: Automatically collects metric data for virtual machine hosts, including CPU and memory usage, with data sampled once per minute.
- Visualization: Offers a Metrics tab for virtual machines to view and analyze CPU and memory metrics over adjustable time periods.

### Log Analytics Tool

Log Analytics is a powerful tool within the Azure portal that allows you to edit and run log queries on data collected by Azure Monitor logs. It provides an interactive environment to analyze the results of these queries.

#### Key Features

- Querying: Enables the creation and execution of log queries to retrieve records matching specific criteria.
- Trend Identification: Helps identify trends and analyze patterns within the collected data.
- Insights: Provides various insights into your data, aiding in troubleshooting and performance optimization.
- Interactive Analysis: Allows for interactive analysis of query results, making it easier to understand and act on the data.

Together, Azure Monitor and the Log Analytics tool offer a robust solution for monitoring, analyzing, and optimizing the performance and availability of your applications and services.
