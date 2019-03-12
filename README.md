# auth0-container

Open your Auth0 account.
Goto Applications, Settings tab.
Copy Cliend ID and Client Secret.

Set enviorment variables to appropriate values 
```code
export AUTH_CLIENT_ID=<applicatio client id> 
export AUTH0_CLIENT_SECRET=<application client secret> 
```

Goto APIs and get 
Auth0 Management API
API Audience

Your API Name
CUSTOM API
API Audience

```code
export AUTH0_DOMAIN=<auth management api address> //https://YOURUSERID.eu.auth0.com/api/v2/ 
export AUTH0_AUDIENCE=<api id>
```
