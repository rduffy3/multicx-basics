---
title: "Azure EOD Personal - Deployment & Setup"
chapter: false
weight: 20
---

## Deployment of your Azure EOD Personal Environment
Azure EOD Personal Deployment is automatically available to all internal Genesys GDemo users. No request is required. 

### Creating Your Configuration
Go to the navigation in GDemo and select "Environments" from the Genesys Engage Cloud menu.
![environments](/images/Environments.jpg)
You will create a configuration and define the settings.
![Provision](/images/EODPersonalNew.jpg)
Select Microsoft Azure as the Cloud Provider.
![chooseAzure](/images/chooseAzureProvider.png)
Select **EOD Personal** as the type of Environment that you want to provision, and then click "Create EOD Personal".
![Type](/images/EODPersonalType.jpg)
Complete the Properties page and click "Provision".
![Properties](/images/EODPersonalTypeDetails.jpg)
It may take a few minutes to provision. This is normal.
![Wait](/images/POCRequested.jpg)
### Provisioning Completed
When finished, you will you will see your new Azure Personal EOD in your list of Live Environments.
![Success](/images/POCSuccessful.jpg)
Note the icon that designates your new EOD as provisioned on Azure.
![myLiveAzure](/images/myLiveAzure.png)
### Retrieving Configurations at later time
At any time you can retrieve your configuration, such as Unit ID, agent password, etc., by going to 'My Live EODs', and then clicking the 'View EOD Configuration' icon.
![EODWorkshopView](/images/EODWorkshopView.jpg)
On the Configuration page, note this button which will give you a PDF version of your configuration.
![ConfigurationSummary](/images/EODWorkshopPDF.jpg)
Note that your Unit Type is designated as Azure.
![AzureType](/images/azureUnitType.png)
### Opening your Azure EOD Personal Portal
Once you have deployed your EOD Personal, open the Azure EOD Portal here:
[Azure EOD Portal](https://portal-1007-westus2.prod001.genesysengage.com/)
The Portal is accessed directly in the browser. Without VPN and without the GDemo View VDI. This is a major distinction between EODs provisoned on Azure and those provisioned on AWS. 