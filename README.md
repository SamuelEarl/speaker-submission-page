# The project in this repo
This project is a rewrite of the project that is built in this tutorial: [Build a Secure CRUD App with ASP.NET Core and React](https://developer.okta.com/blog/2018/07/02/build-a-secure-crud-app-with-aspnetcore-and-react). Instead of using ASP.NET Core and React, this project uses Vue.js, hapi.js, and Neo4j and is Dockerized using Docker Compose.

This project is also built using:

* Starter Kit: https://github.com/SamuelEarl/starter-kit-docker-vue-node-neo4j
* The Okta API package for Node.js apps (okta-sdk-nodejs):
  * [GitHub Repo](https://github.com/okta/okta-sdk-nodejs). NOTE: This package uses the term "Client", but that does not mean the browser. This is not a package for browser frameworks. "Client" in this context means a piece of software that accesses a service that is made available by a server. (See [Client (computing)](https://en.wikipedia.org/wiki/Client_%28computing%29).) This is a package used by the Node.js server.
  * [Okta API wrapper for Node.js Reference](https://developer.okta.com/okta-sdk-nodejs/jsdocs/Client.html)
  * [Users API](https://developer.okta.com/docs/reference/api/users/)
