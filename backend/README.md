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

## BCrypt
```bash
npm i bcrypt
npm i -D @types/bcrypt
```

## Nestjs config
```bash
npm i --save @nestjs/config
```

## TypeORM
```bash
npm install --save typeorm pg @nestjs/typeorm
```

## Migration
```bash
npx typeorm migration:create ./src/migration/create_table_user
npx typeorm migration:create ./src/migration/create_table_state
npx typeorm migration:create ./src/migration/create_table_city
npx typeorm migration:create ./src/migration/create_table_address
npx typeorm migration:create ./src/migration/alter_table_state
```

## Controllers
```bash
npx nest g co state 
```

