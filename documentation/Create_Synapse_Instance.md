# Synapse_AdventureWorks2019
Synapse demo using AdventureWorks2019 data

In this repo we demonstrate some Azure Synapse Analytics functionality using AdventureWorks2019 Database data.

## Create Synapse Instance

Let's create an instance of Synapse.

Search for Synapse in the search box on the top of the Azure portal and click on Azure Synapse Analytics.

On the Azure Synase Analytics page, click the Create button.

![Create Synapse](./../images/CreateSynapse.png)

In the Create Synapse workspace page, select the Subscription, select the Resource group (we recommend selecting the same Resource group you created for the Azure SQL Database, in the previous step of this demo), enter the name for the managed resource group.

![Create Synapse](./../images/CreateSynapseII.png)

On the Workspace details section, enter the workspace name, create a new Data Lake Storage Gen2 account, a new File system and click the Review and create button.

![Create Synapse](./../images/CreateSynapseIII.png)

Once the Validation succeeds, click the Create button and wait until the deployment is completed. Once it is completed, click Go to resource.

![Create Synapse](./../images/CreateSynapseIV.png)

