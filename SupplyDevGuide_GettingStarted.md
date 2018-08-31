# HERE Supply API: Getting Started #

## Getting Here Mobility Account and Credentials ##

To create your account at Here mobility [email the Here support team](mailto:mobility_developers@here.com) and provide your full name and email address.

You'll receive an initial password and verification email to your mailbox.
At a later stage, you'll be able to manage your account via our Here mobility developer portal.

To obtain application user credentials for the Supply API, [email the Here support team](mailto:mobility_developers@here.com) and specify the following:

-   Your application name
-   A URL for a web application or a package/store ID for a mobile app

You will receive: 

-   An application key 
-   An application secret value

Here is an example of what the application key and secret values look like:  

```{"applicationKey": "Casd9nS4WUs90***cCvsurYgtpLEgm8", "applicationSecret": "QcVyN7Wq3HNqWN3DEAI0H***mibtsdUkJ_8zS0skrRHfZyzKbW0gmvjSKgnLt"}```

### Getting an access Token ###

Here is an example of how to create a Supply API access token:

```GET accounts.v1/application/s2s/token?application_key=<application_key>&&application_secret=<application_secret>```

### Sandbox and Production Environments ###

You can use the HERE Mobility Sandbox platform to develop and test your app's functionality without calling the production platform. Requests to the sandbox environment are ephemeral (do not affect the "real world").

The HERE Mobility service directs your app's calls to the sandbox or to the production environment, according to the API key you provide.