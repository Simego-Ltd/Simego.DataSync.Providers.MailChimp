# Simego.DataSync.Providers.MailChimp
Data Sync Connector for MailChimp

## Installing the Connector

To install the Mailchimp connector we have a Data Connector Installer built into Data Sync. To use this you need to have the URL to the zip file containing the connector code.

To get the url navigate to the release page in GitHub, then right click onto the **Simego.DataSync.Providers.MailChimp.zip** file and copy the link.
![Copy link to Connector Zip](https://user-images.githubusercontent.com/63856275/225887220-50672a12-cf1f-4bf9-a2fb-a7e731c7abe6.png "Copy link to Connector Zip")

Now open Data Sync and go to **File** > **Install Data Connector**. Then paste the link into the **Data Connector URL** field and click OK to install the connector.

![Install Connector](https://user-images.githubusercontent.com/63856275/225887133-17a4057c-eb22-4b5e-857a-a767b45c33bf.png "Install Connector")

If the installation was successful you should get a confirmation popup and you now need to close all instances of Data Sync and then re-start the program. 

![Connector Installed Successfully](https://user-images.githubusercontent.com/63856275/225889045-ce2f669b-bb82-4593-bd9a-3a8f47b55b90.png "Connector Installed Successfully")

> If you get an error saying it could not install the connector because it is "Unable to access folder", then this is because the folder is locked by Ouvvi. 
> Please stop your Ouvvi services and try again.

You can now access both of the connectors from the connection window under **Mailchimp**.

## Connect to Mailchimp Lists

Use this connector to return all the lists/audiences you have in your account. This specific connector is read-only.
![Connect to Mailchimp List Provider](https://user-images.githubusercontent.com/63856275/225955497-046c3c2b-f4b4-4baa-9918-b08e6f594230.png "Connect to Mailchimp List Provider")

### Settings
#### APIKey

This is your Mailchimp API Key. You can generate and view your API keys in the API Keys section of your Mailchimp account <a href="https://us1.admin.mailchimp.com/account/api/?_ga=2.160367421.1402420354.1562763503-247507899.1561114757" target="_blank">here. </a>

![Get API Key](https://user-images.githubusercontent.com/63856275/225955258-f3722639-205a-40a3-b2a5-69e5623e6bda.png "Get API Key")

For more information on API Keys in Mailchimp, visit their documentation pages <a href="https://mailchimp.com/help/about-api-keys/" target="_blank">here.</a>


## Connect to Mailchimp Members to add users to your Audience List.

Use this connector to add users to your audience lists.

![Mailchimp List Member Connector](https://user-images.githubusercontent.com/63856275/225887325-77831830-5e76-4c49-b6c5-2139eb6572a7.png "Mailchimp List Member Connector")

<div class="alert alert-info">NB: If you delete users from your audience list you will need to ask them to re-subscribe in order to add them back to your list.</div>

### Settings
#### APIKey

This is your Mailchimp API Key. You can generate and view your API keys in the API Keys section of your Mailchimp account <a href="https://us1.admin.mailchimp.com/account/api/?_ga=2.160367421.1402420354.1562763503-247507899.1561114757" target="_blank">here. </a>

![Get API Key](https://user-images.githubusercontent.com/63856275/225955258-f3722639-205a-40a3-b2a5-69e5623e6bda.png "Get API Key")

For more information on API Keys in Mailchimp, visit their documentation pages <a href="https://mailchimp.com/help/about-api-keys/" target="_blank">here.</a>

#### ListName
This is the audience you wish to connect to.
