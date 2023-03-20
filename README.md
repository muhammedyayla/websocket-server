# How it's built

* /app is the browser application
* /api is a node.js web sockets server
* Web app connects to web sockets server
* On connection, each client is assigned an `id` and a `color`.

# What's in here?

This repository contains two demos which share cursor positions over WebSockets. One using WS in the `main` branch and one using SockJS in the `SockJS` branch.

# Running this sample

This demo includes two applications, a web app, that we serve through Snowpack, and a Node.js webserver. The NPM start task will spin up both the API and the webserver.

```bash
> npm install
> npm run start
```
