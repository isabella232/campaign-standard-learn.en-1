---
title: Trouble shooting the Control Panel
description: The Control Panel allows you to monitor and manage your SFTP storage by instance and allowlist IP addresses.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
recommendations: noDisplay
exl-id: f546f791-a69b-4586-abfa-3e626b8feb17
---
# Trouble shooting the [!UICONTROL Control Panel]

Learn how to troubleshoot issues when using the Control Panel.

## Login and homepage

Issues occurring with login and homepage.

### Symptom: Unable to log in to Adobe Experience Cloud

**What to do:**
The user must locate their [!DNL IMS Org ID] (xxx). The administrator must add the user to the [!UICONTROL product profile] [!DNL “Campaign-xxx-Admins”] for each instance that they would like to manage. If the user is an admin of all instances, they must add themselves as *[!UICONTROL user]*.

### Symptom: Links in the [!UICONTROL Adobe Experience Cloud Home] to access [!UICONTROL Control Panel] do not appear for a user 

**Cause:**
Users won’t see the links until they are added as users to [!UICONTROL product profile] `Campaign-xxx-Administrators/Admin`

**What to do:**
The administrator must add the user to the [!UICONTROL product profile] *[!DNL Campaign-xxx-Admins]* for each instance that they would like to manage. If the user is an admin of all instances, they must add themselves as *[!UICONTROL user]*. 

### Symptom: An Instance is not listed in the [!UICONTROL Control Panel]

**Cause:**
Most likely user must be added as a *[!UICONTROL user]* Product Profile `Campaign-xxx-Administrators/Admin` for the instance that is missing

**What to do:**
The administrator must add the user to the Product Profile `Campaign-xxx-Admins` for each instance that they would like to manage. If the user is an admin of all instances, they must add themselves as *[!UICONTROL user]*.

### Helpful videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Check [!DNL IMS Org ID] (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*How to add an administrator to the [!UICONTROL product profile] [!DNL administrators] to be able to use [!UICONTROL Control Panel] (01:03 min)*

### Helpful Documentation

* [Discover the [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
* [Managing permissions to the [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Establishing Connection to SFTP Server (Client or API)

Connecting to SFTP servers requires:

* [!UICONTROL allow listing] the IP address from which you are connecting to the SFTP server  
* Private/public key pair that must be registered with Adobe Campaign
* If connecting to the SFTP server directly, you need SFTP client software

### Helpful Documentation {#helpful-docs}

* [Logging into your SFTP server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
