# Obtaining a ClientId and Client Secret for Google

To configure Google OAuth connections (Google Apps and Google) you will need to register Auth0 with Google on the API Console.

##1. Log in into API Console
Go to the [API Console](https://code.google.com/apis/console#access), and click on the __Create an OAuth2 client ID__ button:

![](img/goog-apiconsole-1.png)

---

##2. Complete information about your instance of Auth0

![](img/goog-apiconsole-2.png)

These URLs and information don't need to point to Auth0. It is information for your reference.

---

##3. Setup your callback URL into Auth0:

	https://@@account.namespace@@/login/callback

![](img/goog-apiconsole-3.png)

---

##4. Get your ClientId and ClientSecret

Once the application is registered, enter your new `ClientId` and `ClientSecret` into the connection settings in Auth0.

![](img/goog-apiconsole-4.png)


##5. Enable Admin SDK Service

If you are planning to connect Google Apps enterprise domains, you need to enable the __Admin SDK__ service as follows:

![](img/goog-apiconsole-5.png)
