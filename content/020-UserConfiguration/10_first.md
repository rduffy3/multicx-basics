---
title: "AWS EOD Personal - Deployment & Setup"
chapter: false
weight: 10
---

## Access
AWS EOD Personal Deployment is automatically available to all internal Genesys GDemo users. No request is required. 

## Creating Your Configuration

Go to the navigation in GDemo and select "Environments" from the Genesys Engage Cloud menu. 
![environments](/images/Environments.jpg)

You will create a configuration and define the settings.
![Provision](/images/EODPersonalNew.jpg)
Select AWS as the Cloud Provider
![Provider](/images/chooseAWSProvider.png)
Select **EOD Personal** as the type of Environment that you want to provision, and then click "Create EOD Personal".
![Type](/images/EODPersonalType.jpg)
Complete the Properties page and click "Provision". 
![Properties](/images/EODPersonalTypeDetails.jpg)
It may take a few minutes to provision. This is normal.
![Wait](/images/POCRequested.jpg)
## Provisioning Completed
When finished, you will see your new Personal EOD in your list of Live Environments.
![Success](/images/POCSuccessful.jpg)
Note the icon that designates your new EOD as provisioned on AWS.
![LiveIcon](/images/awsLiveIcon.png)
## Retrieving Configurations at a Later Time
At any time you can retrieve your configuration, such as Usit ID, agent password, etc., by going to 'My Live EODs', and then clicking the 'View EOD Configuration' Icon. 
![EODWorkshopView](/images/EODWorkshopView.jpg)
On the Configuration page, note this button which will give you a PDF version of your configuration. 
![ConfigurationSummary](/images/EODWorkshopPDF.jpg)
Note that your Unit Type is designated as AWS.
![UnitType](/images/awsUnitType.png)

# Connecting to your AWS EOD Personal
Once you have deployed your AWS EOD Personal, the following will show you how to connect and login using your specifically assigned users.

## Open your EOD within Horizon View
1. Navigate to: [view.demo.genesys.com](https://view.demo.genesys.com/) on your browser.    
2. Log into Horizon client with your GDemo credentials.
3. Select PURE as domain.
4. Click on the EOD Desktop pool. 
You will also see the GDemo pool, but please make sure to select the EOD Desktop pool for the Workshop.
5. The virtual desktop will load in the Horizon View session.
Note: EOD environments must be accessed through GDemo on View. Direct local access will not work properly.

## Before starting, check the Softphone
Once the View Session is open, check in the bottom right to make sure the Genesys Softphone is running. You will see this icon if it is:
![taskbaricon](/images/SoftPhoneCorner.png)
If not running, then start it from the Softphone shortcut on the desktop.
![desktopicon](/images/eodSoftPhoneShortcut.png)
## Log into Agent Desktop
From within the View Session, launch Chrome from one of the 3 shortcuts on the desktop.
![Shortcuts](/images/POCShortcuts.png)
The browser will open directly to the Portal at gtsdemo.genesyscloud.com.
From the Portal select "Agent Desktop"
![AgentDesktop](/images/Portal.png)
## AWS EOD Personal users login information
Reference your EOD configuration or PDF and log into Agent Desktop with: 
username = unique Username in format of **u[Unit ID]agt1@pec.com** as specified in your EOD configuration. 
password = 'Agents Password' as specified in your EOD configuration. 
Note: Tenant field should be empty. 
![EODWorkshop](/images/EODWorkshopAdLogin.jpg)
Make the Agent ready on all channels. 
![AgentReady](/images/WWE9_Agent_Ready.png)
