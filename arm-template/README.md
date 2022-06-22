## Deploy

### Pre-requisites

- Access to an existing [Azure subscription](https://docs.microsoft.com/en-us/azure/guides/developer/azure-developer-guide#understanding-accounts-subscriptions-and-billing)
- If you don't have an Azure subscription, create an [Azure free account](https://azure.microsoft.com/free/?ref=microsoft.com&utm_source=microsoft.com&utm_medium=docs&utm_campaign=visualstudio) before you begin.

### Install

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fappvia%2Fwayfinder-azure-tests%2Fmain%2Farm-template%2Fazuredeploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fappvia%2Fwayfinder-azure-tests%2Fmain%2Farm-template%2FcreateUiDefinition.json" rel="nofollow"><img src="https://aka.ms/deploytoazurebutton" alt="Deploy To Azure" style="max-width: 100%;" rel="noopener noreferrer" target="_blank"></a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fappvia%2Fwayfinder-azure-tests%2Fmain%2Farm-template%2Fazuredeploy.json" rel="nofollow"><img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true" alt="Visualize" style="max-width: 100%;" target="_blank"></a></p>

### Delete Installation

To delete this app installation, simply delete the resource group used by the deployment above:

1. Identify the resource group you specified in the deployment e.g.
    <img style="max-width: 100%;" src="images/Azure-deployment-complete-subscription.png"/>

1. [Delete the resource group](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal#delete-resource-groups)
