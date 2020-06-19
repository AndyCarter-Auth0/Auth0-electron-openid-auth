# Sample Electron App With PKCE

This is a sample application to demonstrate integrating an Electron App with Auth0, using Authorisation Code with PKCE flow. 

It is based on the following blog post [Securing Electron Applications with OpenID Connect and OAuth 2.0](https://auth0.com/blog/securing-electron-applications-with-openid-connect-and-oauth-2/), however uses Authorisation Code With PKCE flow for securing the application with Auth0.

You will need to follow the blog post for details on configuring your application and API in your Auth0 tenant.

This sample app uses http://myapp rather than http://localhost as per the blog post. This is to allow the consent screen in Auth0 to be bypassed.

![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) You will need to ensure http://myapp/callback is registered as an allow callback URL in your application in your Auth0 tenant

## Installation

Download the code to a local folder and update the ENV json file with the values for your application and tenant.

Using bash or PowerShell, navigate to the src folder and run

```bash
npm i -D electron
npm install
```

## Usage

```bash
npm run
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
MIT
