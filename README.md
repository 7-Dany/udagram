# Udagram

## Welcome! 👋

**Thanks for checking out the project ❤**

**Live Site URL**

- [Udagram](http://dany-udagram.s3-website-us-east-1.amazonaws.com)

**Note**

- **Be sure to update you .env file with environment variables**

### Table of contents

- [Overview](#overview)
    - [The Project](#The-Project)

- [My Process](#my-process)
    - [Built with](#built-with)
    - [Scripts to run](#scripts-to-run)
    - [Endpoints](#endpoints)
    - [Dependencies](#dependencies)
    - [Environment Variables](#environment-variables)
## Overview

### The Project

You will be able to:

- Create user with name , email and password
- Authenticate user to access some routes
- Get user by its id
- Get all feed items
- Get feed resource by id
- Get a signed url to Put new file in the bucket
- Create feed with metadata

## My Process

### Built with

- **TypeScript**
- **Express**
- **Node**
- **Postgres**
- **Angular**

### Scripts to run
1. __For The Back-End__

- To start the server
  ```
  npm run start
  ```
- To start development
  ```
  npm run dev
  ```
- To build TypeScript
  ```
  npm run tsc
  ```
- To deploy the app
  ```
  npm run deploy
  ```
- To build the app
  ```
  npm run build
  ```
2. __For The Front-End__

  - To start the app
    ```
    npm run start
    ```
  - To lint the app
    ```
    npm run lint
    ```
  - To Do unit Testing for the app
    ```
    npm run test
    ```
  - To deploy the app
    ```
    npm run deploy
    ```
  - To build the app
    ```
    npm run build
    ```
  - To do end-to-end testing
    ```
    npm run e2e
    ```
    
### Endpoints
1. User Routes
- To Authenticate User '/user/login'  [POST]
- To Create New User '/user' [POST]

2. Feed Routes
- To Create Feed '/feed' [POST]
- To Get Signed-up url to save new file to bucket '/feed/signed-url/:fileName' [GET]
- To Get Feed by id '/feed/:id' [GET]
- To Get All Feeds '/feed' [GET]

### Dependencies

1. __For The Back-End__

   - typescript
   - Express
   - pg
   - reflect-metadata
   - sequelize
   - sequelize-typescript
   - dotenv
   - jsonwebtoken
   - bcrypt
   - jasmine
   - jasmine Spec Reporter

3. __For The Front-End__

   - typescript
   - angular
   - ionic
   - rxjs
   - zone.js
   - codelyzer
   - jasmine
   - jasmine Spec Reporter

### Environment Variables

- POSTGRES_USERNAME=YOUR-DATABASE-USERNAME
- POSTGRES_PASSWORD=YOUR-DATABASE-PASSWORD
- POSTGRES_HOST=YOUR-DATABASE-HOST
- POSTGRES_DB=YOUR-DATABASE-ENGINE (ex:postgres)
- AWS_BUCKET=YOUR-AWS-BUCKET-NAME
- AWS_REGION=YOUR-AWS-REGION
- AWS_PROFILE=default
- JWT_SECRET=YOUR-SECRET-TOKEN
- URL=YOUR-ELASTIC-BEANSTALK-URL
