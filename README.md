# Gamification Platform Backend 

## About the project

This is a standalone backend for Gamification platform built by Codebrahma based on Node (Hapi JS) and GraphQL.
MongoDB will be used as backend.

## Bootstraped using [Hapi Starter Kit](https://github.com/Codigami/hapi-starter-kit) | Hapi based REST application boilerplate, uses async/await


## Requirements
 - [node.js](https://nodejs.org/en/download/current/) >= `8.4.0`
 - [yarn](https://yarnpkg.com/en/docs/install) >= `0.27.5`
 - [docker](https://docs.docker.com/engine/installation/#supported-platforms)
    - Docker is optional and is required only if you want to develop and deploy using Docker

## Getting Started
```bash
# Install dependencies
$ yarn
```

```bash
# Start Server
# Set environment variables defined in `config/custom-environment-variables.json`
$ yarn start
```

```bash
# Run Tests
$ yarn test
```

## Docker

#### Development
```bash
# copy sample.dev.env to dev.env
$ cp bin/sample.dev.env bin/dev.env
```

```bash
# Start Server
$ bash bin/development.sh
```

### Tests

```bash
# copy sample.test.env to test.env
$ cp bin/sample.test.env bin/test.env
```

```bash
# Run Tests
$ bash bin/test.sh
```


## More Tasks
```bash
# Run lint
yarn lint
```

## Documentation
- `hapi-swagger` self documents all the APIs.
- Visit `http://localhost:3030/documentation` to access the documentation after starting the server.

## Issues
Please feel free to open an issue if you can have any questions or trouble using this starter kit.

## Contributions
Contributions are all welcome and encouraged. For code contributions submit a pull request with unit test.

## License
This project is licensed under the [MIT License](https://github.com/Codebrahma/gamification-platform-backend/blob/master/LICENSE)
