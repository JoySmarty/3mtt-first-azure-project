# 3mtt-first-azure-project

# Azure Free Tier Account Setup Report

**Module:** Cloud Computing Fundamentals
**Student:** *[Your Name]*
**Date:** *[Submission Date]*

---

# 1. Introduction

This report documents the process of creating and configuring a Microsoft Azure Free Tier account. The objective was to gain practical experience using the Azure Portal, deploying cloud resources, understanding Azure governance, monitoring costs, and implementing security best practices.

During this exercise, an Azure Storage Account was successfully deployed in the **UK South** region and the Azure Portal was explored to understand the core services available to cloud administrators.

---

# 2. Azure Free Tier Overview

The Microsoft Azure Free Tier allows new users to explore Azure services without incurring significant costs.

## Free Tier Benefits

| Feature                | Description                                                              |
| ---------------------- | ------------------------------------------------------------------------ |
| Free Credit            | USD $200 credit available for the first 30 days (eligible new accounts). |
| 12-Month Free Services | Selected Azure services remain free for the first 12 months.             |
| Always Free Services   | Several Azure services remain free within monthly usage limits.          |

### Examples of Free Services

| Service                       | Free Allocation |
| ----------------------------- | --------------- |
| B1s Virtual Machine           | 750 hours/month |
| Blob Storage (LRS)            | 5 GB            |
| Managed Disk                  | 64 GB SSD       |
| Azure Database for PostgreSQL | 750 hours/month |
| Outbound Data Transfer        | 15 GB/month     |

These benefits provide an excellent environment for learning cloud technologies while minimizing costs.

---

# 3. Azure Account Creation

The Azure account was created using the Microsoft Azure Free Account registration process.

The following verification steps were completed:

* Microsoft account sign in
* Email verification
* Phone number verification
* Identity verification
* Payment method (credit/debit card) verification
* Acceptance of Microsoft Azure terms and conditions

After verification was complete, the Azure subscription became active and access to the Azure Portal was granted.

**Figure 1:** Azure Subscription Overview

*(Insert Screenshot 1 here)*

---

# 4. Azure Portal Navigation

After logging into the Azure Portal, the interface was explored to become familiar with Azure services.

Key areas of the portal include:

* Home Dashboard
* Resource Groups
* Storage Accounts
* Virtual Machines
* Microsoft Entra ID
* Cost Management + Billing
* Azure Monitor
* Marketplace

The search bar located at the top of the portal makes it possible to quickly locate services, resources, and documentation.

Azure also uses **breadcrumb navigation** to display the current location within the portal.

Example:

Home → Resource Groups → AzureLabRG → Storage Account

Breadcrumb navigation makes it easier to move between resources without repeatedly returning to the home page.

**Figure 2:** Azure Portal Home

*(Insert Screenshot 2 here)*

---

# 5. Dashboard Customization

The Azure Dashboard was customised to improve accessibility and efficiency.

Useful tiles were added for:

* Resource Groups
* Storage Accounts
* Cost Management
* Recent Resources
* Azure Advisor

Custom dashboards help administrators monitor important resources from a single interface.

**Figure 3:** Custom Azure Dashboard

*(Insert Screenshot 3 here)*

---

# 6. Resource Group Creation

A Resource Group was created to logically organise Azure resources.

Resource Group Name:

AzureLabRG

Region:

UK South

Using Resource Groups allows related Azure resources to be managed together throughout their lifecycle.

**Figure 4:** Resource Group

*(Insert Screenshot 4 here)*

---

# 7. Storage Account Deployment

A Storage Account was successfully deployed using the Azure Portal.

Configuration:

* Storage Type: Standard
* Performance: Standard
* Replication: Locally Redundant Storage (LRS)
* Region: UK South

The Storage Account can be used to store:

* Blobs
* Files
* Queues
* Tables

Deploying storage resources demonstrates one of Azure's core infrastructure services.

**Figure 5:** Storage Account Deployment

*(Insert Screenshot 5 here)*

---

# 8. Billing and Cost Management

Azure provides Cost Management tools that allow users to monitor cloud spending.

The Cost Management dashboard displays:

* Current spend
* Forecasted spend
* Resource costs
* Subscription usage

To avoid unexpected charges, a budget should be created.

Example Budget Configuration:

* Budget Amount: USD $150
* Alert Threshold: 75%
* Notification: Email alert

This provides early warning before the free credit is exhausted.

**Figure 6:** Cost Management Dashboard

*(Insert Screenshot 6 here)*

**Figure 7:** Budget Alert Configuration

*(Insert Screenshot 7 here)*

---

# 9. Security Best Practices

Cloud security is based on a Shared Responsibility Model.

Microsoft is responsible for:

* Physical data centres
* Networking infrastructure
* Hardware
* Hypervisor security

The customer is responsible for:

* User accounts
* Identity management
* Data protection
* Resource configuration
* Access permissions

Additional security best practices include:

* Enable Multi-Factor Authentication (MFA)
* Use strong passwords
* Apply Role-Based Access Control (RBAC)
* Enable Microsoft Defender recommendations
* Regularly review Azure Security Center recommendations
* Monitor activity logs

Implementing these controls reduces the risk of unauthorised access.

**Figure 8:** Microsoft Entra ID / MFA Settings

*(Insert Screenshot 8 here)*

---

# 10. Challenges Encountered

During the setup process, several challenges were encountered:

* Understanding Azure terminology.
* Learning how Resource Groups organise resources.
* Navigating the Azure Portal.
* Understanding pricing and free tier limitations.

These challenges were overcome using Microsoft Learn documentation and Azure Portal guidance.

---

# 11. Troubleshooting

| Issue                      | Resolution                                        |
| -------------------------- | ------------------------------------------------- |
| Verification delays        | Waited for Microsoft verification to complete.    |
| Unable to locate services  | Used the Azure Portal search bar.                 |
| Cost management unfamiliar | Explored Cost Management tutorials and dashboard. |
| Resource deployment errors | Verified region and subscription availability.    |

---

# 12. Completion Checklist

✓ Azure Free Tier account created

✓ Email verified

✓ Phone verified

✓ Payment method verified

✓ Azure Portal explored

✓ Dashboard customised

✓ Resource Group created

✓ Storage Account deployed

✓ Cost Management reviewed

✓ Budget alert configured

✓ Security best practices documented

✓ Screenshots captured

---

# 13. Conclusion

This project provided practical experience with Microsoft Azure cloud services. An Azure Free Tier account was successfully created, and key Azure features including Resource Groups, Storage Accounts, Cost Management, and Azure security practices were explored.

The exercise strengthened my understanding of cloud resource management, governance, cost monitoring, and security. These foundational skills are essential for future work in cloud computing, DevOps, and Microsoft Azure administration.

---

# References

* Microsoft Learn – Azure Fundamentals
* Microsoft Azure Documentation
* Azure Free Account Documentation
* Microsoft Learn – Azure Cost Management
* Microsoft Learn – Microsoft Entra ID

