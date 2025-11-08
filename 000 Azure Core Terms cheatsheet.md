# Azure Core Concepts & Certification Terms Cheat Sheet

A concise list of essential Azure terms.

| **Term**                                   | **Simple Definition**                                                | **Category**      |
| ------------------------------------------ | -------------------------------------------------------------------- | ----------------- |
| Availability Zone                          | Independent physical datacenter within a region for fault isolation. | Core Architecture |
| Region                                     | Geographical area containing one or more data centers.               | Core Architecture |
| Resource Group                             | Logical container for managing related Azure resources.              | Core Architecture |
| Fault Domain                               | Group of hardware sharing a single point of failure.                 | Core Architecture |
| Update Domain                              | Set of resources updated together during maintenance.                | Core Architecture |
| Scalability                                | Ability to increase or decrease resources as needed.                 | Core Architecture |
| Elasticity                                 | Automatic scaling up or down based on demand.                        | Core Architecture |
| High Availability (HA)                     | Ensures services remain accessible even during failures.             | Core Architecture |
| Load Balancing                             | Distributes incoming traffic evenly across resources.                | Core Architecture |
| Redundancy                                 | Multiple copies of components or data for reliability.               | Core Architecture |
| Fault Tolerance                            | System continues operating even if part fails.                       | Core Architecture |
| Fault Tolerance                            | System survives failure; Focuses on continuity of service            | Core Architecture |
| Fault Isolation                            | System contains failure; Focuses on damage control                   | Core Architecture |
| Latency                                    | Delay in data transfer or processing.                                | Performance       |
| Throughput                                 | Amount of data processed in a given time.                            | Performance       |
| Resiliency                                 | System’s ability to recover from disruptions.                        | Core Architecture |
| Failover                                   | Automatic switch to backup system when primary fails.                | Reliability       |
| Disaster Recovery (DR)                     | Restoring services and data after a major outage.                    | Reliability       |
| Backup                                     | Copy of data used to restore after loss or corruption.               | Reliability       |
| Geo-replication                            | Duplicating data across geographic regions.                          | Reliability       |
| SLA (Service Level Agreement)              | Contract defining service uptime guarantees.                         | Governance        |
| Virtual Machine (VM)                       | On-demand, scalable computing instance.                              | Compute           |
| Scale Set                                  | Group of identical VMs for load distribution.                        | Compute           |
| Container Instance                         | Lightweight, isolated compute environment.                           | Compute           |
| App Service                                | Platform for running web and API apps without managing servers.      | Compute           |
| Availability Set                           | Logical grouping to protect VMs from hardware failures.              | Compute           |
| Blob Storage                               | Object storage for unstructured data like images and videos.         | Storage           |
| File Share                                 | Shared file storage accessible over SMB protocol.                    | Storage           |
| Disk Type                                  | Defines disk performance (Standard/Premium).                         | Storage           |
| IOPS                                       | Measure of input/output performance for storage.                     | Storage           |
| Hot/Cool/Archive Tiers                     | Storage pricing and access speed options.                            | Storage           |
| Snapshot                                   | Point-in-time backup of a disk or data.                              | Storage           |
| Managed Disk                               | Automatically managed storage for VMs.                               | Storage           |
| Ephemeral Disk                             | Temporary storage that resets when VM is redeployed.                 | Storage           |
| Virtual Network (VNet)                     | Private network for Azure resources.                                 | Networking        |
| Subnet                                     | Logical partition within a VNet.                                     | Networking        |
| Network Security Group (NSG)               | Firewall rules controlling inbound/outbound traffic.                 | Networking        |
| Route Table                                | Defines network traffic flow.                                        | Networking        |
| Public/Private IP                          | Identifies resources for external/internal access.                   | Networking        |
| Peering                                    | Connects VNets privately without VPN.                                | Networking        |
| VPN Gateway                                | Connects on-premises network to Azure over VPN.                      | Networking        |
| ExpressRoute                               | Private, dedicated connection to Azure.                              | Networking        |
| Application Gateway                        | Layer 7 load balancer for web apps.                                  | Networking        |
| Azure Firewall                             | Managed network security service.                                    | Networking        |
| Azure AD (Entra ID)                        | Microsoft’s identity and access management service.                  | Security          |
| Tenant                                     | Dedicated Azure AD instance for an organization.                     | Security          |
| Subscription                               | Billing and resource boundary in Azure.                              | Governance        |
| RBAC                                       | Role-based access control for permissions.                           | Security          |
| Managed Identity                           | Provides credentials for Azure resources automatically.              | Security          |
| Conditional Access                         | Controls access based on user conditions or risk.                    | Security          |
| MFA                                        | Multi-factor authentication for enhanced security.                   | Security          |
| PIM                                        | Manages and audits privileged admin roles.                           | Security          |
| Azure Policy                               | Enforces governance rules across resources.                          | Governance        |
| Key Vault                                  | Securely stores keys, secrets, and certificates.                     | Security          |
| Azure Monitor                              | Centralized monitoring service for performance and health.           | Management        |
| Log Analytics                              | Collects and queries log data from resources.                        | Management        |
| Activity Log                               | Tracks all control-plane operations in Azure.                        | Management        |
| Metrics                                    | Numeric performance data from resources.                             | Management        |
| Alerts                                     | Notify users of critical conditions.                                 | Management        |
| Cost Management                            | Monitors and controls cloud spending.                                | Management        |
| Resource Tagging                           | Adds metadata labels for organization and tracking.                  | Governance        |
| ARM Template                               | JSON file that defines Azure resources for deployment.               | Automation        |
| Blueprint                                  | Predefined set of resources for compliance.                          | Governance        |
| Geo-Zone Redundant Storage (GZRS)          | Stores data across regions and zones for durability.                 | Storage           |
| Locally Redundant Storage (LRS)            | Keeps data copies within a single data center.                       | Storage           |
| Zone-Redundant Storage (ZRS)               | Copies data across multiple availability zones.                      | Storage           |
| Read-Access Geo-Redundant Storage (RA-GRS) | Allows read access to replicated data in another region.             | Storage           |
| Consistency                                | Ensures all copies of data reflect the same information.             | Storage           |
| Durability                                 | Likelihood of data remaining intact over time.                       | Storage           |
| Vertical Scaling                           | Increasing power of existing resources.                              | Performance       |
| Horizontal Scaling                         | Adding more resources to handle load.                                | Performance       |
| Auto-Scaling                               | Automatically adjusts capacity based on demand.                      | Performance       |
| Management Group                           | Organizes subscriptions for unified governance.                      | Governance        |
| Compliance                                 | Adherence to data protection and security laws.                      | Governance        |
| Data Residency                             | Where data is physically stored.                                     | Governance        |
| Data Sovereignty                           | Legal control of data within a specific jurisdiction.                | Governance        |
| Security Baseline                          | Minimum configuration standard for compliance.                       | Governance        |
| Tagging Strategy                           | Consistent labeling for easy resource tracking.                      | Governance        |

---
