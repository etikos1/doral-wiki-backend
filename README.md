
## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

 Clone Repo 

## Installation

### Prerequisites

- Node.js (version 18.18.0)
- npm (version 9.8.1) 
- Docker
- Docker Compose 


### Install neccessary dependencies

```bash

* npm i -g @nestjs/cli

* npm install axios class-validator sqlite3 typeorm


### Running the app

```bash
# development

$ npm run start

## View the app

* GET content from Wikipedia: http://localhost:3000/feed?year=2024&month=05&day=08 
 (date can be changed to GET different featured contents from Wikipedia)

* GET translated content : http://localhost:3000/feed/translate/es?year=2024&month=06&day=01
 (change date accordingly to see translation from different dates)

# watch mode
$ npm run start:dev


## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

$ npx cypress open

    or

Or using Docker:

docker-compose run cypress


Docker Setup

* To set up and run the application using Docker, follow these steps:

- Build and start the Docker containers:

docker-compose up --build

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
