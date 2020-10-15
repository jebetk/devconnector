# DevConnector

> Social network for developers

This is a full stack small social network application using Node.js, Express, React, Redux and MongoDB along with ES6+. It includes authentication, profiles and forum posts.

# Quick Start 🚀

```
Add a default.json file in config folder with the following
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

## Install server dependencies

```
npm install
```

## Install client dependencies

```
cd client
npm install
```

## Run both Express & React from root

```
npm run dev
```
## Build for production

```
cd client
npm run build
```
