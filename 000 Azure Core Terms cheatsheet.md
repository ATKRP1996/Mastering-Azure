# Azure Core Concepts

A concise and clear explanation of essential Azure terms grouped by core categories. Each definition is simple, two-to-three lines for easy understanding and memorization.

---

## 🌐 Core Architecture

| **Term**                   | **Explanation**                                                                                                                              |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **Availability Zone**      | A physically separate datacenter within a region. It helps in fault isolation and ensures services remain available even if one zone fails.  |
| **Region**                 | A geographic location containing one or more Azure datacenters. Choosing the right region impacts performance, cost, and compliance.         |
| **Resource Group**         | A logical container that holds related Azure resources. It helps manage, monitor, and delete resources together easily.                      |
| **Fault Domain**           | A group of hardware within a datacenter sharing a single failure point. It ensures resources are spread out to reduce simultaneous failures. |
| **Update Domain**          | A set of resources updated together during maintenance. Azure ensures not all instances are updated at once to prevent downtime.             |
| **Scalability**            | The system’s ability to grow or shrink resources based on demand. It ensures performance stability under varying workloads.                  |
| **Elasticity**             | Automatic scaling up or down of resources depending on real-time usage. It optimizes cost and performance dynamically.                       |
| **High Availability (HA)** | Ensures applications remain accessible even during component or zone failures using redundancy and failover.                                 |
| **Load Balancing**         | Evenly distributes incoming network traffic across multiple servers or instances to maintain high performance and reliability.               |
| **Redundancy**             | Storing multiple copies of data or having backup components to avoid service interruption during hardware or software failures.              |
| **Fault Tolerance**        | The system continues to operate smoothly even if part of it fails, ensuring uninterrupted service delivery.                                  |
| **Fault Isolation**        | Limits the impact of a failure to a specific area so it doesn’t spread, keeping other parts of the system functional.                        |
| **Resiliency**             | The system’s ability to recover quickly from disruptions or outages and return to normal operations.                                         |
| **Failover**               | Automatic switching of workloads from a failed system to a backup system without manual intervention.                                        |

---

## ⚡ Performance & Reliability

| **Term**                          | **Explanation**                                                                                                                       |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Latency**                       | The delay or time it takes for data to travel from source to destination. Lower latency means faster response and better performance. |
| **Throughput**                    | The amount of data processed or transferred within a given time period, representing overall system efficiency.                       |
| **Disaster Recovery (DR)**        | The process of restoring data and services after a major outage or disaster, ensuring business continuity.                            |
| **Backup**                        | A copy of data used to restore original information after loss, corruption, or accidental deletion.                                   |
| **Geo-replication**               | Automatically duplicates data across geographically distant regions for protection and quick recovery during regional outages.        |
| **SLA (Service Level Agreement)** | A formal contract specifying uptime, performance, and availability guarantees provided by Azure services.                             |
| **Vertical Scaling**              | Increasing the size or capacity of an existing resource (like upgrading VM specs) for better performance.                             |
| **Horizontal Scaling**            | Adding more resources (like multiple VMs) to distribute workload and improve performance under high demand.                           |
| **Auto-Scaling**                  | Automatically adjusts the number of running instances based on current load, saving cost and maintaining efficiency.                  |

---

## 💾 Storage

| **Term**                                       | **Explanation**                                                                                                     |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Blob Storage**                               | Object-based storage used for unstructured data like images, videos, and backups. It’s highly scalable and durable. |
| **File Share**                                 | Managed file storage accessed using SMB protocol, allowing multiple VMs to share the same files securely.           |
| **Disk Type**                                  | Defines the performance of storage disks — Standard (HDD) or Premium (SSD) based on workload needs.                 |
| **IOPS**                                       | Measures input/output operations per second, representing how fast data can be read or written.                     |
| **Hot/Cool/Cold/Archive Tiers**                | Storage tiers for cost optimization — Hot for frequent, Cool/Cold for infrequent, and Archive for long-term data.   |
| **Snapshot**                                   | Captures a point-in-time backup of data or disks, helping restore systems to a specific earlier state.              |
| **Managed Disk**                               | Azure-managed virtual disks that simplify storage management, backup, and replication for VMs.                      |
| **Ephemeral Disk**                             | Temporary local storage attached to VMs that resets on reboots or redeployment, useful for non-persistent data.     |
| **Geo-Zone Redundant Storage (GZRS)**          | Stores data across multiple zones and regions to ensure high durability and availability.                           |
| **Locally Redundant Storage (LRS)**            | Keeps data replicated within a single datacenter for protection from local hardware failures.                       |
| **Zone-Redundant Storage (ZRS)**               | Copies data synchronously across availability zones to protect against datacenter-level failures.                   |
| **Read-Access Geo-Redundant Storage (RA-GRS)** | Provides read access to a replicated copy of data in another region during an outage.                               |
| **Consistency**                                | Ensures all copies of data remain synchronized so every user sees the same information.                             |
| **Durability**                                 | Reflects how safely data is stored and how resistant it is to corruption or loss over time.                         |

---

## 🖧 Networking

| **Term**                         | **Explanation**                                                                                  |
| -------------------------------- | ------------------------------------------------------------------------------------------------ |
| **Virtual Network (VNet)**       | A private network that connects and isolates Azure resources securely in the cloud.              |
| **Subnet**                       | A logical segment within a VNet that divides resources for organization and security.            |
| **Network Security Group (NSG)** | A set of firewall rules controlling inbound and outbound traffic for Azure resources.            |
| **Route Table**                  | Defines the routing path for network traffic between subnets and resources.                      |
| **Public/Private IP**            | Unique identifiers that allow resources to communicate internally or externally.                 |
| **Peering**                      | Connects two VNets privately, allowing secure communication without going over the internet.     |
| **VPN Gateway**                  | Establishes secure encrypted connections between on-premises networks and Azure VNets.           |
| **ExpressRoute**                 | Provides a private, dedicated high-speed connection between on-premises and Azure data centers.  |
| **Application Gateway**          | A Layer 7 load balancer that manages web traffic efficiently with security and routing features. |
| **Azure Firewall**               | A cloud-native, managed network security service that protects Azure resources from threats.     |

---

## 🔒 Security & Identity

| **Term**                                 | **Explanation**                                                                                      |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Azure AD (Entra ID)**                  | Microsoft’s cloud-based identity and access management service for authentication and authorization. |
| **Tenant**                               | A dedicated Azure AD instance that represents an organization’s identity environment.                |
| **RBAC (Role-Based Access Control)**     | Defines who can access which resources and at what permission level.                                 |
| **Managed Identity**                     | Provides Azure services with an automatically managed identity to access other resources securely.   |
| **Conditional Access**                   | Enforces access policies based on conditions like location, device state, or risk.                   |
| **MFA (Multi-Factor Authentication)**    | Adds an extra layer of security by requiring two or more verification methods for login.             |
| **PIM (Privileged Identity Management)** | Controls and audits high-level administrative roles to reduce security risks.                        |
| **Key Vault**                            | Securely stores encryption keys, secrets, and certificates in a controlled environment.              |

---

## 🧠 Management & Monitoring

| **Term**            | **Explanation**                                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------------- |
| **Azure Monitor**   | Provides a comprehensive view of application and infrastructure health through logs, metrics, and alerts. |
| **Log Analytics**   | Collects and analyzes telemetry data from resources to identify performance issues and trends.            |
| **Activity Log**    | Tracks all actions performed on Azure resources for auditing and troubleshooting.                         |
| **Metrics**         | Numeric data showing real-time performance and resource utilization trends.                               |
| **Alerts**          | Automated notifications triggered by defined conditions or thresholds in resource performance.            |
| **Cost Management** | Helps monitor, analyze, and optimize Azure spending efficiently.                                          |

---

## 🧾 Governance & Compliance

| **Term**              | **Explanation**                                                                            |
| --------------------- | ------------------------------------------------------------------------------------------ |
| **Subscription**      | Defines a billing and resource boundary that groups Azure services under one account.      |
| **Azure Policy**      | Ensures compliance by enforcing rules and configurations across Azure resources.           |
| **Blueprint**         | Predefined templates and policies to deploy compliant environments quickly.                |
| **Resource Tagging**  | Assigns custom labels to resources for better organization, cost tracking, and automation. |
| **Management Group**  | Groups multiple subscriptions together for unified policy and access control.              |
| **Compliance**        | Adherence to data protection, privacy, and security laws across geographies.               |
| **Data Residency**    | Specifies where organizational data is physically stored to meet regulatory requirements.  |
| **Data Sovereignty**  | Ensures data remains under the legal jurisdiction of its country of origin.                |
| **Security Baseline** | A predefined set of security settings that serve as a minimum protection standard.         |
| **Tagging Strategy**  | A structured way of labeling resources consistently for governance and reporting.          |
