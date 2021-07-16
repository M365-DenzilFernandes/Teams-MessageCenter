# Teams-MessageCenter
* Get Message Center and Post to Teams Channel
* Get Message Center and Post to Text File

# -------------------------------------------

# Azure AD App Registration
* Create an app registration and grant it the following API Permissions.
* Add an Application Permission to Office 365 Management API's and Select ServiceHealth.Read - Admin Consent Required.
<img src="https://github.com/M365-DenzilFernandes/M365-MessageCenter-PowerBI/blob/main/PBI-MessageCenter-4.png"  style="max-width:100%;">
Note you will need the AAD Tenant ID, Application ID and Secret to be used in either of the solutions below.

# -----OPTION 1----------------------

# Create Teams Incoming Webhook
You will need the url for 

# Import Power Automate Flow 1 - Message Center to Teams Channel
[Download the package](https://github.com/M365-DenzilFernandes/Teams-MessageCenter/raw/main/MicrosoftTeams-MessageCenter(v1.0).zip) and update the queries
* You only need to update the connection uri with the teams incoming webhook and update the tenant id, client id and client secret where applicable.

# -----OPTION 2----------------------

# Teams-MessageCenter-To-Teams-Channel
Gets Message Center and Post to Teams Channel

# Import Power Automate Flow 2 - Mesage Center to Text File
[Download the package](https://github.com/M365-DenzilFernandes/Teams-MessageCenter/raw/main/MicrosoftTeams-MessageCenter(v1.0)-To-TextFile.zip) and update the queries
* You only need to update the connection uri with the teams incoming webhook and update the tenant id, client id and client secret where applicable.



