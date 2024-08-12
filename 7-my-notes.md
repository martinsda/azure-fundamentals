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
Differences in connectivity options.

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
