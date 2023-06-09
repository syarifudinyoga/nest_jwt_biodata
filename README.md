<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://coveralls.io/github/nestjs/nest?branch=master" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Installation

```bash
$ npm install
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

## ========================= Additional ================================
## Install Prisma (For Database)

```bash
# with npm
$ npm install prisma -D
$ npm install @prisma/client

# with yarn
$ yarn add prisma -D
$ yarn add @prisma/client

# then run
$ npx prisma
$ npx prisma init
```

## Push Prisma to Database

```bash
# run prisma after add prisma/schema.prisma
$ npx prisma db push 

# test generate prisma
$ npx prisma generate
```

## Create Module & Service Prisma

```bash
# create module prisma
$ nest g mo prisma

# create service prisma
$ nest g s prisma
```

## Setup JWT

```bash
# install npm for setup jwt
$ npm install @nestjs/passport passport passport-local
$ npm install @types/passport-jwt -D
$ npm install @nestjs/jwt
```

## Auth File

```bash
# create module auth
$ nest g mo auth

# create service auth
$ nest g s auth

# create module auth
$ nest g co auth

# create guard 
$ nest g gu auth/jwt-auth

# install bcrypt (Make pipe for transform hash to bcrypt)
$ npm install bcrypt
$ npm install @types/bcrypt -D

# install class validator and transformer
$ npm install class-validator
$ npm install class-transformer
```

## Add Open API (Swagger)

```bash
# create swagger
$ npm install --save @nestjs/swagger swagger-ui-express
```

## Execute Swagger

```bash
# execute
http://localhost:3000/openapi/

#source example
https://www.mistercoding.com/post/nestjs/setup-jwt-using-nestjs-prisma-mysql-database/
```

## Create Todo
```bash
# create module todo
$ nest g mo todo

# create service todo
$ nest g s todo

# create module todo
$ nest g co todo
```