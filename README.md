# NodeExpressReact-Starter
A project starter using Node, Express, Babel, React, Webpack that compiles ES2015

## What does it come with
This start comes with basic Express setup routing to '/', which will serve simple React component that shows `Hello World`.
Babel is setup to compile ES2015. Webpack is configured with devServer that can watch client changes for convenient development.
More features can be seen in package.json scripts.

## What does it not come with
This project starts with very basic requirements for flexibility. 
This project does not come with any test framework.

## Usage
Install all dependencies by `npm install`.

### Building
- To build only the client code (react components and client.js), `npm run build`.
- To compile only server side code, `npm run compile`.

### Dev
- To run devServer for client development, `npm run dev`. This will also automatically watch for changes in client code.
- To run server, `npm babel-run`. This will compile & run the server.js without compiling to any output.

### Prod
- To run server in production, use `npm start`, which will also trigger `build` and `compile` to build first. Don't use `npm babel-run` in production as it results in heavy memory usage and startup performance issues.

## Placeholder
There are several places to change the project name:
- package.json/name,description,author
- webpack.config.json/title
