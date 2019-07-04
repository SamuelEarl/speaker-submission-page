# The project in this repo
NOTE: I should also have a look at the following tutorials. The ones that use a single-page app along with a backend server show you how to secure your app as much as possible (because there is no such thing as 100% secure):
* [Build User Registration with Node, React, and Okta](https://developer.okta.com/blog/2018/02/06/build-user-registration-with-node-react-and-okta)
* [How to Securely Manage Users in Your Node App](https://developer.okta.com/blog/2018/06/26/securely-manage-users-node-app). This allows you to tap into Okta's APIs and allow users to manage their own profiles. This also shows how to use a `.env` file, but does NOT show how to use the dotenv package to work with `.env` packages.
* [Build a Node.js API with TypeScript (real-time chat app)](https://developer.okta.com/blog/2019/05/07/nodejs-typescript-api). This is a very recent post that shows how things have changed since the PKCE auth update. (Hint: I don't think anything has changed from the developer's perspective or what I would need to do to configure Okta's auth flow, but in case you were wondering this tutorial walks you through the new process.) This one combines Node.js and React and uses the okta-sdk-nodejs package to create a real-time chat app. This also shows how to use a `.env` file along with the dotenv package.
* [Build a Secure To-Do App with Vue, ASP.NET Core, and Okta](https://developer.okta.com/blog/2018/01/31/build-secure-todo-app-vuejs-aspnetcore). This one combines Vue.js and ASP.NET Core.

This project is a rewrite of the project that is built in this tutorial: [Build a Secure CRUD App with ASP.NET Core and React](https://developer.okta.com/blog/2018/07/02/build-a-secure-crud-app-with-aspnetcore-and-react). Instead of using ASP.NET Core and React, this project uses Vue.js, hapi.js, and Neo4j and is Dockerized using Docker Compose.

This project is also built using:

* Starter Kit: https://github.com/SamuelEarl/starter-kit-docker-vue-node-neo4j
* The Okta API package for Node.js apps (okta-sdk-nodejs):
  * [GitHub Repo](https://github.com/okta/okta-sdk-nodejs). NOTE: This package uses the term "Client", but that does not mean the browser. This is not a package for browser frameworks. "Client" in this context means a piece of software that accesses a service that is made available by a server. (See [Client (computing)](https://en.wikipedia.org/wiki/Client_%28computing%29).) This is a package used by the Node.js server.
  * [Okta API wrapper for Node.js Reference](https://developer.okta.com/okta-sdk-nodejs/jsdocs/Client.html)
  * [Users API](https://developer.okta.com/docs/reference/api/users/)
