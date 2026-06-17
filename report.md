# Azure Free Tier Account Setup Report

## Project Overview

This project introduces the fundamentals of Microsoft Azure by creating and configuring an Azure Free Tier account. The objective was to gain hands-on experience with Azure Portal navigation, cloud governance, identity management, resource deployment, cost monitoring, and security best practices.

---

# Objectives

The objectives of this project were to:

* Create an Azure Free Tier account.
* Explore the Azure Portal interface.
* Understand Azure subscriptions and Resource Groups.
* Learn the basics of Microsoft Entra ID and Role-Based Access Control (RBAC).
* Deploy a basic Azure resource.
* Explore Azure Cost Management and Billing.
* Understand the Azure Shared Responsibility Model.
* Learn best practices for securing an Azure account.

---

# Account Registration

I created a Microsoft Azure Free Tier account using my Microsoft account.

During the registration process, Azure required the following verification steps:

* Email verification
* Phone number verification
* Identity verification
* Payment method verification

After successful verification, the Azure Free subscription became active and was available in the Azure Portal.

**Evidence**

* Screenshot: Active Azure Subscription

---

# Azure Portal Exploration

After signing in, I explored the Azure Portal to become familiar with its interface and navigation.

The following services were located using the search bar and navigation menu:

| Azure Service             | Purpose                                     |
| ------------------------- | ------------------------------------------- |
| Home                      | Displays recent resources and notifications |
| Subscriptions             | Manages Azure subscriptions                 |
| Resource Groups           | Organizes Azure resources                   |
| Storage Accounts          | Stores blobs, files, queues, and tables     |
| Microsoft Entra ID        | Identity and access management              |
| Cost Management + Billing | Monitors cloud spending                     |
| Search                    | Quickly finds Azure services                |

The Azure Portal provides a centralized interface for deploying, managing, and monitoring cloud resources.

---

# Dashboard Customization

To make frequently used resources easier to access, I customized my Azure dashboard by pinning commonly used services.

The dashboard includes shortcuts to:

* Resource Group
* Storage Account
* Cost Analysis

This customization improves efficiency by reducing navigation time.

---

# Governance

Azure organizes cloud resources using subscriptions and Resource Groups.

## Subscription

A subscription provides billing, access control, and resource management boundaries.

## Resource Group

I created the following Resource Group:

| Property | Value         |
| -------- | ------------- |
| Name     | rg-devops-lab |
| Region   | UK South      |

The Resource Group serves as a logical container for related Azure resources.

---

# Identity and Access Management

Azure uses Microsoft Entra ID to manage identities and authentication.

I explored the following areas:

* Users
* Groups
* Roles
* Role-Based Access Control (RBAC)

RBAC allows administrators to assign permissions based on roles instead of granting unrestricted access.

Examples include:

* Owner
* Contributor
* Reader

This approach follows the Principle of Least Privilege by ensuring users receive only the permissions required to perform their tasks.

---

# Region Selection

I selected **UK South** as the deployment region.

## Reason for Selection

UK South is one of the closest Azure regions to Nigeria, providing lower network latency and improved performance compared to more distant regions.

Choosing a nearby region also helps improve user experience and application responsiveness.

---

# Resource Deployment

To gain practical experience with Azure resource deployment, I created a Storage Account.

## Resource Details

| Property      | Value                           |
| ------------- | ------------------------------- |
| Resource Type | Storage Account                 |
| Performance   | Standard                        |
| Redundancy    | Locally Redundant Storage (LRS) |
| Region        | UK South                        |

The deployment demonstrated the Azure resource creation workflow, including validation, configuration, deployment, and monitoring.

---

# Cost Management and Billing

Azure provides tools to monitor cloud spending and avoid unexpected charges.

I explored:

* Cost Analysis
* Budgets
* Billing Overview

A budget was configured to monitor resource usage and provide alerts before spending exceeds expected limits.

This helps ensure that resources remain within the Azure Free Tier limits.

---

# Azure Free Tier Benefits

The Azure Free Tier provides several benefits for new users.

| Benefit              | Description                                          |
| -------------------- | ---------------------------------------------------- |
| Free Account         | Access to Azure services at no initial cost          |
| Popular Services     | Free usage limits on selected services for 12 months |
| Always Free Services | Selected services remain free within monthly quotas  |
| Cost Monitoring      | Budgets and spending alerts                          |
| Learning Environment | Hands-on experience with real Azure infrastructure   |

These benefits make Azure suitable for learning cloud computing while minimizing costs.

---

# Shared Responsibility Model

The Shared Responsibility Model defines which security responsibilities belong to Microsoft and which belong to the customer.

For the deployed Storage Account:

## Microsoft Azure Responsibilities

* Physical datacenter security
* Hardware maintenance
* Network infrastructure
* Power and cooling
* Availability of Azure Storage

## My Responsibilities

* Managing user access
* Configuring RBAC permissions
* Protecting stored data
* Monitoring account activity
* Securing authentication credentials

This shared approach ensures that both Azure and the customer contribute to maintaining a secure cloud environment.

---

# Security Best Practices

To improve the security of the Azure account, the following best practices were reviewed:

* Enable Multi-Factor Authentication (MFA)
* Use a strong, unique password
* Apply Role-Based Access Control (RBAC)
* Follow the Principle of Least Privilege
* Monitor account activity regularly
* Configure spending alerts to detect unexpected resource usage

These practices reduce the risk of unauthorized access and accidental overspending.

---

# Troubleshooting

| Issue                        | Resolution                                           |
| ---------------------------- | ---------------------------------------------------- |
| Resource name already exists | Use a globally unique storage account name           |
| Subscription not visible     | Verify the correct Microsoft account is signed in    |
| Resource deployment failed   | Check region availability and configuration settings |
| Budget option unavailable    | Ensure the correct subscription is selected          |

---

# Completion Checklist

* [x] Azure Free Tier account created
* [x] Email verification completed
* [x] Phone verification completed
* [x] Azure subscription activated
* [x] Azure Portal explored
* [x] Resource Group created
* [x] Microsoft Entra ID explored
* [x] Azure region selected
* [x] Storage Account deployed
* [x] Cost Management explored
* [x] Budget configured
* [x] Shared Responsibility Model reviewed

---

# Conclusion

This project provided practical experience with the Microsoft Azure platform by completing the initial setup of an Azure Free Tier account and deploying a cloud resource. Through this exercise, I gained an understanding of Azure governance, resource organization, identity management, cost monitoring, and cloud security responsibilities. These foundational skills will support future learning in cloud engineering, DevOps, and Azure infrastructure management.
