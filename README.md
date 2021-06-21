# TODO

- [ ] Create mongoDB and connect
- [ ] Create user controller, service and model
- [ ] Create auth flow using passport
- [ ] Implement passport authentication
- [ ] Add JWT support to create tokens
- [ ] Create unique sessionid strings
- [ ] Connect with TMDB API using the sessionID string and the token value
- [ ] Implement dynamic query to retrieve info from TMDB API

## Description

API to use WTW React App, this API will have authentication connected with Passport and MongoDB, using the basic auth flow Auth0. This API will also connect with TMDB API in order to create a complex query system to retrieve data from their API, the auth instructions from the TMDB API must be followed in order to connect with a sessionID and a token in order to use the API to retrieve movies ant tv shows information. In this first version of the API will only consult movies and tv shows by genre, year, querystring or country. This API will only store user information and different collections(movies or tv shows) created by a user.

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ yarn install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).
