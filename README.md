# 3mtt-first-azure-project

## Resource Cleanup (Cost Control and Best Practice)

To ensure that no unexpected charges occur after completing this Azure Free Tier setup, it is important to properly clean up all deployed resources.

Cloud resources continue to run and may incur costs even if they are not actively used. Therefore, deleting unused resources is a key part of good cloud governance.

### Steps to Delete Resources

The following steps were used to safely remove resources created during this project:

1. Sign in to the Azure Portal.
2. Navigate to **Resource Groups** using the search bar.
3. Select the resource group created for this project (e.g., `rg-devops-lab`).
4. Review all resources contained within the resource group.
5. Click **Delete resource group**.
6. Type the exact name of the resource group to confirm deletion.
7. Click **Delete** to permanently remove all associated resources.

### What Gets Deleted

Deleting the resource group automatically removes all resources inside it, including:

* Storage Account
* Any test deployments
* Associated configurations and metadata

### Importance of Cleanup

Performing resource cleanup ensures:

* No unintended billing after the Free Tier usage period
* Proper cloud cost management
* Good security hygiene by removing unused assets
* Compliance with cloud best practices (Infrastructure lifecycle management)

This step is a critical part of working in cloud environments such as Azure, especially when using free credits or trial subscriptions.
