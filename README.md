
A progressive Node.js framework for building efficient and scalable server-side applications.

NPM Version Package License NPM Downloads CircleCI Coverage Discord Backers on Open Collective Sponsors on Open Collective  Support us 

Description
Nest framework TypeScript starter repository.

Installation
$ npm install
Running the app
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
Test
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
Techstack
NestJS (v9)
TypeORM (0.3.11)
Swagger (Open API)
PostgreSQL
Supertest
Features
1. TypeORM with Database Migrations

For use it, edit in package.json. Find typeorm:generate-migration and edit end name of file. Example npm run typeorm -- -d ./typeOrm.config.ts migration:generate ./migrations/init

After it, run typeorm:generate-migration

You will see file in folder migrations. Named like this 1673879532073-init.ts

Run database migration with npm run typeorm:run-migrations

2. Integration/Service Test

Make e2e you want. Example in employee.e2e.test. For use it run npm run test:e2e.
Support
Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please read more here.

Stay in touch
Author - Kamil Myśliwiec
Website - https://nestjs.com
Twitter - @nestframework
License
Nest is MIT licensed.





< data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
<span class="navbar-toggler-icon"></span>
</button>

            
            
            
      






