# react-auth-app

Full-stack application demonstrating user login and registration using JWT authentication.

Technologies:

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for the frontend
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend
- [MongoDB](https://www.mongodb.com/) for the database
- [Redux](https://redux.js.org/basics/usagewithreact) for state management between React components

## Configuration

Set the MONGO_URI from your [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) database in the .env file.

```javascript
MONGO_URI = "YOUR_MONGO_URI_HERE"
```

## Quick Start

```javascript

// Install [Redux DevTools Chrome extension](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?utm_source=chrome-ntp-icon). It is recommended to use Google Chrome as your development browser for this project and you will need to have the above extension installed to be able to run the project locally. It is recommended for any extension as it makes it easy to debug Redux logic.

// Install dependencies for server & client
npm install && npm run client-install

// Run client & server
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000 by default
```
