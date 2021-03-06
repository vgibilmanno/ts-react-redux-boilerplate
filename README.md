# TypeScript React/Redux Boilerplate

This boilerplate sets up a basic structure for quick starting your projects.
This boilerplate provides you with

* React and TypeScript project created with [CRA](https://github.com/facebook/create-react-app)
* State management with [Redux](https://github.com/reactjs/react-redux)
* Routing with react-router and react-router-redux
* Components showing how to use redux and how to handle side-effects
* ExpressJs service
* Docker support

## Getting Started

To get started clone this repository and install the dependencies for both applications.

Execute this command on each directory (Client/Server)

```
npm install or yarn install
```

## Run the Applications

Start the applications by executing this command on each directory.

```
npm start or yarn start
```

For the React app browse to [`localhost:3000`][local-client-url].

The ExpressJs service API is available under [`localhost:9050`][local-service-url].


[local-client-url]: http://localhost:3000
[local-service-url]: http://localhost:9050

## Docker

Docker is fully optional in this boilerplate but a basic support is still provided.

### Individual containers
If you want to use Docker you can individually build docker images for each directory and run them separately

```
docker build .
docker run %ID%
```

### Compose
If you don't want to build containers separately and prefer to wire both up, you can use the compose file in the root directory.

Use the following commands

```
docker-compose build
docker-compose up -d
```
