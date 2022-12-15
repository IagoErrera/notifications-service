# Notification Service

## Description
It is a microservice develop with Node.Js and the framework Nest.Js, implementing a notification service.
This is my first project in Nest.Js and my first contact with microsservices.

## Core technologies
- Node.Js
- Nest.Js
- Jest
- Prisma ORM
- SQLite

## Patterns used
- In Memory Database
  - Used to test the application without interfer with the real database
- Factory
  - Used to simplify and standardize the creation of enitities in tests
- Mapper
  - Used to convert entities between application and persistence layer
- View Model
  - Used to convert entities to the exposed model
 
 ## Commands
 ### To run project
 ```
 npm run start
 ```
 or 
 ```
 npm run start:dev
 ```
 
 ### To run tests
 ```
 npm run test
 ```
 or
 ```
 npm run test:watch
 ```
