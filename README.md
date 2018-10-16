# Realtime Web Notifications Demo

This application sends a web notification whenever there is push activity on a GitHub repo. Article: https://pusher.com/tutorials/html5-notification-api

## Getting Started

1. Clone this repository and `cd` into it.
2. Execute `npm install` to download dependencies.
3. See tutorial for notes on how to get the required keys from Pusher and how to set up the webhook for GitHub.
4. Open `main.js` and `variables.env` and update them with your Pusher credentials.
5. Run `node server.js` to start the Express server.
6. Run `http-server -p 5001` to serve the app frontend on port 5001.
7. Open up http://localhost:5001 in your web browser.

## Pre-requisites

- [Node.js](https://nodejs.org/en) and npm
- [http-server](https://www.npmjs.com/package/http-server)

## Built With

- [Pusher Channels](https://pusher.com/docs) - Realtime features

## Licence

[MIT](https://opensource.org/licenses/MIT)

