## Setup Instructions

1. Run `yarn` or `npm install`
2. Include the firebase service account token file in the `firebase` directory
3. Change the details in `config.js` to that of your auth0 and firebase applications
4. Run `node server` to start the server which runs at port `1337`
5. To test the firebase token endpoint, send a GET request to `http://localhost:1337/auth/firebase` with the Auth0 access token recieved from the client in the Authorization header
