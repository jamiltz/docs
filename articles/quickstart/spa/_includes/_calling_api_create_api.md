## Create a Resource Server (API)

In the [APIs section](${manage_url}/#/apis) of the Auth0 Dashboard, click the **Create API** button. Provide a **Name** and **Identifier** for your API and be sure to choose the RS256 signing algorithm. The identifier you set will later be used as the `audience` when configuring your `auth0.WebAuth` instance.

![Create API](/media/articles/api-auth/create-api.png)