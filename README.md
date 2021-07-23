# Teams-MessageCenter
* Get Message Center and Post to Teams Channel
* Get Message Center and Post to Text File

###### 📺 Watch Hugo Bernier and myself provide a demonstration how to combine various tools to provide a more engaging meeting experience.
 <a href="https://www.youtube.com/watch?v=j0-Yh0fH8vM" target="_blank"><img src="https://i9.ytimg.com/vi/j0-Yh0fH8vM/mqdefault.jpg?sqp=CMjN7IcG&rs=AOn4CLC3892xNE6HSynplqvnn-tjguE1vg" 
alt="Teams Like a Boss" border="10" /></a>

## Prerequisites
* Azure AD App Registration
* Power Automate Premium Connectors

## Azure AD App Registration
* Create an app registration and grant it the following API Permissions.
* Add an Application Permission to Office 365 Management API's and Select ServiceHealth.Read - Admin Consent Required.
* Note you will need the AAD Tenant ID, Application ID and Secret to be used in either of the solutions below.

<img src="https://github.com/M365-DenzilFernandes/M365-MessageCenter-PowerBI/blob/main/PBI-MessageCenter-4.png"  style="max-width:100%;">

## Option 1---Teams-MessageCenter-To-Teams-Channel
Gets Message Center and Post to Teams Channel

### 1. Create Teams Incoming Webhook
* Go to the Channel that will receive the posts from Message Center. If a channel doesn't exist, create one and add an incoming webhook connector. 
* Click [here](https://docs.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/how-to/add-incoming-webhook) for steps on how to create an incoming webhook

### 2. Import Power Automate Flow 1 - Message Center to Teams Channel
* [Download the package](https://github.com/M365-DenzilFernandes/Teams-MessageCenter/raw/main/MicrosoftTeams-MessageCenter(v1.0).zip) and Import into Power Automate.
* You only need to update the connection uri with the teams incoming webhook and update the tenant id, client id and client secret where applicable.

## Option 2---Teams-MessageCenter-To-Text File
Gets Message Center and Post to Text File

### 1. Import Power Automate Flow 2 - Mesage Center to Text File
* [Download the package](https://github.com/M365-DenzilFernandes/Teams-MessageCenter/raw/main/MicrosoftTeams-MessageCenter(v1.0)-To-TextFile.zip) and Import into Power Automate.
* Update the tenant id, client id and client secret where applicable. The begining part of the flow
* Also Update the location where you want to save this file.
