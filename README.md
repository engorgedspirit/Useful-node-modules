# Useful-node-modules
Here is a list of most useful node libraries. Welcome to npm world.

### What is node
Node is a form of JavaScript which is not associated with any webpage, i.e. it does not have a DOM or document object as root element. But node is the same JavaScript
when it is run as an independent code. 

### What is npm
npm is a package manager for developed for node. It is simple to setup and use, also it has vast majority of <strong>Open source libraries</strong> which can do any 
functions from generating colored text to fetching weather data of your location  or build a whole new Browser or app.

### Why node
Main reason is that it is very easy to setup and most importantly it is open source code. We can contribute to it tooo.

### installation
You can download node from the link given below

https://nodejs.dev/en/download/

### Setup
After installing to initialize node use this command

<em>npm init</em>

To install a package

<em>npm install package_name</em>


# Useful Packages List

## 💻 Frontend frameworks

1. [React](https://reactjs.org/) [React-dom](https://reactjs.org/docs/react-dom.html), and [React-router-dom](https://reactrouter.com/web/guides/quick-start) are popular frontend frameworks that offer developers the ability to manage individual components of a webpage. They allow for more efficient reloading and updating of sections without needing to reload the entire page.
2. [Vue](https://vuejs.org/!)
 is a highly versatile frontend framework that is praised for its speed and ease of use. It is often paired with Vue-router and Vuex, which add additional functionality and complexity to its capabilities.
3. [Svelte](https://svelte.dev/)
 is a new frontend framework that has gained attention for its ability to compile declarative components into highly efficient JavaScript that selectively updates the DOM.
4. [Angular](https://angular.io/)
 is a powerful frontend framework that is built on a component-based architecture, providing developers with an extensive toolset and highly scalable applications. It is known for its steep learning curve but is a popular choice among experienced developers.
5. [Ember.js](https://emberjs.com/)
 is a comprehensive frontend framework that is highly regarded for its convention over configuration approach. It is equipped with many features such as two-way data binding, routing, and computed properties, making it ideal for building ambitious web applications.
6. [Next.js](https://nextjs.org/)
 is a lightweight and production-ready frontend framework that is built on top of React. It is often used for building server-rendered React applications and provides features such as automatic code splitting, static site generation, and serverless functions.

## Styling frameworks
1. [Bootstrap](https://getbootstrap.com/) is a widely used CSS framework that provides developers with the ability to create responsive and mobile-first sites. Although it is relatively bulky in size, it is also highly intuitive and powerful, with many modern UI kits based on it.

2. [Tailwind](https://tailwindcss.com/) is a utility-first CSS framework that is designed for rapid UI development. It offers extensive customization options and is built to be highly flexible and easy to use.

3. [Styled-components](https://styled-components.com/) is a CSS-in-JS tool that bridges the gap between components and styling, providing developers with a functional and reusable way to style their components. Other popular styling frameworks include [Foundation](https://foundation.zurb.com/), [Bulma](https://bulma.io/), [Materialize](https://materializecss.com/), and [Ant Design](https://ant.design/). If you prefer to write Vanilla CSS, you can use a CSS extension language like SASS to extend its features.

4. [Material Design](https://material.io/design) is a Google-created design system that is widely used for building consistent and visually appealing user interfaces across all platforms. It includes pre-built components such as buttons, menus, and cards, making it a popular choice for many developers.

5. [Semantic UI](https://semantic-ui.com/) is a modular and responsive CSS framework that is built on human-friendly HTML. It provides developers with an extensive set of UI components, including forms, grids, and menus, as well as a theming system for customizing the look and feel of their app.

6.[Chakra UI](https://chakra-ui.com/) is a simple and accessible component library that is designed to provide developers with all the building blocks they need to create great-looking React applications. It includes customizable components and supports dark mode out of the box.

## 🧑‍💻 Backend frameworks

1. [Express](https://expressjs.com/) is a minimalist web framework that is optimized for Node.js. It is highly customizable and unopinionated, with many features available as plugins. It is often referred to as the standard server framework for Node.js.

2. [Hapi](https://hapi.dev/) is a powerful backend framework that is built on top of the Express framework. It is designed to help developers build scalable and efficient applications with minimal overhead and full out-of-the-box functionality.

3. [Sails](https://sailsjs.com/) is a popular backend MVC framework for Node.js. It is equipped with many features such as support for data-driven APIs and a scalable, service-oriented architecture, making it a popular choice for many developers.

4. [Cors](https://www.npmjs.com/package/cors) is a middleware for Node.js that is used to enable cross-origin resource sharing with various options. It provides a Connect/Express middleware that can be used to manage and optimize API resource sharing.

5. [Axios](https://axios-http.com/docs/intro) is a promise-based HTTP client for the browser and Node.js. It simplifies HTTP requests and responses by providing a simple and intuitive API. 

6. [Body-parser](https://www.npmjs.com/package/body-parser) is a middleware that extracts the entire body portion of an incoming request stream and exposes it on req.body as something easier to interface with.

7. [Django](https://www.djangoproject.com/) is a high-level Python web framework that encourages rapid development and clean, pragmatic design. It includes an ORM, a templating system, and a powerful admin interface, among other features.

8. [Ruby on Rails](https://rubyonrails.org/) is a web application framework written in Ruby. It follows the Model-View-Controller (MVC) pattern, and includes features such as ActiveRecord (an ORM), ActionMailer (for sending emails), and ActiveSupport (a set of utility classes).

9. [Laravel](https://laravel.com/) is a PHP web application framework that emphasizes elegant syntax, developer productivity, and modern PHP practices. It includes features such as an ORM, a templating engine, and a robust routing system.

## 🧩API services

1. [GraphQL](https://graphql.org/): GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. It provides a complete description of the data in your API, giving clients the power to ask for exactly what they need.

2. [FastAPI](https://fastapi.tiangolo.com/): FastAPI is a modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints. It is built on top of Starlette for the web parts and Pydantic for the data parts.

3. [LoopBack](https://loopback.io/): LoopBack is a highly extensible, open-source Node.js framework for building APIs and microservices. It provides a set of CLI tools for generating models, data sources, and controllers, as well as a built-in explorer for testing your API endpoints.

4. [Restify](http://restify.com/) is a Node.js web service framework that's optimized for building semantically correct RESTful web services that are ready for production use at scale. Restify optimizes for introspection and performance.

14. [Morgan](https://github.com/expressjs/morgan): Morgan is an HTTP request logger that stores HTTP requests, providing you with concise insight into how your app is being used and where there could be potential errors.

## ✍ Loggers
1. [Winston](https://github.com/winstonjs/winston): Winston is a logger for just about everything, with support for multiple means of transport. It's been out there longer than Morgan, has a bigger community of maintainers, and more downloads.

2. [Bunyan](https://github.com/trentm/node-bunyan): Bunyan is a simple and fast JSON logging library for Node.js services. It includes features such as log levels, child loggers, and stream-based output.

3. [Log4j](https://logging.apache.org/log4j/2.x/): Log4j is a Java-based logging utility that provides a flexible API for logging messages to multiple destinations, such as console, file, and email.

## 🤝 Web sockets

1. [Socket.IO](https://socket.io/): Socket.IO enables real-time, bidirectional, and event-based communication on every platform, browser, or device, focusing equally on reliability and speed.

2. [WS](https://github.com/websockets/ws): WS is a simple-to-use, fast, and thoroughly tested WebSocket client and server implementation that's a great, less abstract, and bare alternative to Socket.IO.

3.[Phoenix Channels](https://hexdocs.pm/phoenix/channels.html): Phoenix Channels is a real-time communication library built into the Phoenix web framework for Elixir. It provides a clean API for creating channels, which can be used to send and receive messages between clients and servers.

4. [Pusher](https://pusher.com/): Pusher is a hosted service for building real-time web applications. It provides a simple API for sending and receiving messages over WebSockets, as well as a set of client libraries for different programming languages.
