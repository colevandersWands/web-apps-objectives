# Web Apps Objectives

drafting learning objectives and project outline for the [web-apps](https://github.com/hackyourfuturebeglium/web-apps) re-write

## open questions

- how generate docs for the API
- how to generate a dependency diagram for the backend so students can visualize the connections between files
- best/simplest way to have unit tests for routes

---

## Group Project

the outline and constraints for the module's 3-week group project: A web app using the file system for data storage, Express.js for the server, and a vanilla frontend:

- _Language Level_\*:
  - _backend_: built-in node modules (fs, path, util.promisify), everything is a function (no classes), ...
  - _frontend_: like last module
- _Environment_: backend, node. frontend, modern browser.
- _Technologies_: node, express, github actions, heroku, ...
- _Starter_: a repository containing folder structures for the front and backend, a configuration folder, a main index.js for deployment, and a github action for deploying to heroku
- _Assessment Criteria_: ...

> - a subset of JavaScript/Node adequate to build the project. students should limit their study to this language subset so they can focus on skill integration instead of extra language or paradigm complexity. Features not in the language subset can fall into different categories including: applicable to the task but out of scope, irrelevant to the task, or counterproductive (like using classes when a project is functional, or AJAX if a project is focusing on fetch)

---

## Learning Objectives

the module has multiple learning objectives determined by the sub-skills required to complete the module's project. they all have priorities/depths to help students and coaches can manage their efforts.

- 🥚: a student can apply this skill comfortably within the module's learning task with access to references. A learning task submitted at the end of the module should demonstrate proficiency in these objectives.
- 🐣: a student can apply this skill with effort and frequent support from references. A learning task submitted at the end of the module should demonstrate partial application of these skills.
- 🐥: a student understands the basic zoomed-out idea of this skill but may not be comfortable or proficient applying it. A learning task submitted at the end of the module may include attempts at applying these skills.
- 🐔: learning this skill is not required for the module's learning task but is relevant, if the student shows appropriate mastery of 🥚, 🐣 and 🐥 objectives. A learning task submitted at the end of the module should not demonstrate these skills if the higher priorities are not accounted for.

the objectives:

- 🥚 **Entry Points**: A student can identify the entry points for their app: npm scripts, first line of first file to run, configuration, server starting, routing
- 🥚 **Persistence**: A student can explain what persistence is and how it is used in the backend of a web app. A student can implement persistence using the backend's file system.
- 🥚 **VSCode Debugger**: a student can pause and step through a Node.js scripts and APIs using the VSCode debugger.
- 🥚 **Callbacks**: A student is familiar with callbacks and can trace/complete simple scripts that use callbacks to work with the file system
- 🥚 **Promisification**: a student can convert built-in node modules from consuming callbacks being async functions.
- 🥚 **Client/Server Architecture**: A student can draw a diagram of their project explaining how the front- and back-ends connect, and can generalize this idea to any web app they use.
- 🥚 **HTTP**: A student can explain these basic notions of the HTTP protocol ...
- 🥚 **Postman**: A student can use Postman to test and inspect HTTP request/response cycles.
- 🥚 **Function Roles**: a student can explain and apply these 4 (maybe more?) function roles in their backend code:
  - _controllers_: like event handlers, but for HTTP requests. (like event handlers in the frontend)
  - _middleware_: do things with a request before it is handled. (no frontend analogy)
  - _data access_: read/write from your data source and return the prepared data, in this module the data source is the file system. (like api calls in the frontend)
  - _logic_: pure functions that transform data and have unit tests. (same as for the frontend)
- 🥚 **NPM Modules**: a student can find, install, require and use an NPM module in their projects
- 🥚 **Express.js**: a student can
  - use middleware
  - `.get/post/put/delete`
  - route params
  - request body
  - send response
  - Express Router
  - listen a new server
  - static serving
- 🥚 **API Documentation**: A student can use JSDoc-style comments to document their API, and a documentation tool to build API documentation
- 🐣 **File System**: a student can read, write and append to .txt files. and can parse, manipulate and re-save data stored in a .json file.
- 🐣 **Data Validation**: A student can validate data sent in a request to the backend before saving it to a .json file
- 🐣 **CI Deployment**: a student can set up a deployment for their web apps and connect it to their repository using a CI action so `main`/`master` is always deployed.
- 🐣 **RESTful Routes**: A student can implement RESTful routes in Express.js, including using the correct `app._` verbs.
- 🐣 **Authentication**: A student can explain the principles of authentication and can contribute to a group project that has basic authentication
- 🐣 **Authentication vs. Authorization**: A student can explain the difference and how it is implemented in their projects
- 🐣 **Environmental Variables**: A student can explain what an environmental variable is, how they're configured, and what they're used for
- 🐥 **Backend Configuration**: A student can use environmental variables to launch their backend in different modes.
- 🐥 **Testing Routes**: A student can explain how tests for API routes work, and can write routes that pass given tests. A student can also write tests for a route that already exists.
- 🐔 **CLI Apps**: a student can complete a simple CLI app that takes user input from the command line and accesses the file system
- 🐔 **`node-fetch`**: a student make API requests from the backend, and use the data in their web apps
