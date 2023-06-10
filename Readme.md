# Simple checkout store

A simple checkout store, with the features

## How To RUN

Project is in 2 directory `frontend` and `backend`.

## Run Backed

- inside the backend directory on your terminal
- run `npm install` to install all dependencies
- run `npm run build` to build the project
- run `npm run start` to start the project

## Run Frontend

- inside the frontend directory on your terminal
- run `npm install` to install all dependencies
- run `npm run build` to build the project
- run `npm run start` to start the project

### Frontend

    - View products
    - Checkout
    - Make payment

### Backend

    - API to simulate checkout
    - API to make payment
    - API to get all transactions

# Technology

## Frontend

    - NextJS
    - React
    - TailWindCSS
    - AntD css

### project stucture

The frontend uses default nextjs folder structure

## Backend

    - NestJS
    - Typescript
    - PostgressDb
    - Redis
    - Docker

### project stucture

The backend uses clean achitecture and Domain driven design principles

## folder structure

    - root
        - src
            - application
            - domain
            - infrastructure
            - presensation
            - common
            - tests
                - unit-tests
                - integration-tests

# Design Pattern

    - Application of Solid principle
    - Clean Achitecture
    - Application of Domain driven design principles

# Deployment

## Backend deployment

post requirement - postgress database - redis cache database

# deployment via docker and azure container service ( similar to aws fargate)

    - push you code to github
    - login to azure portal
    - create a service called azure container app service
    - wait for the service to be provision
    - click on continous deployment on azure
    - connect your github account
    - select the repository
    - specify the part to the docker file
    - select where to push the container image to, recommend select dockerhub, then enter your username and password
    - click ok
    - wait for the deployment to complete
    - configure environment varable
    - To edit and add environment varable
    - click on containers from the resource tabs
    - click on edit and deploy
    - select the container,
    - navigate to environment
    - add new environment varables or edit previous on
    - click on save changes

## Frontend deployment

post requirement
environment varable to payment gateway (you can find it on env.example)
# deployment to netlify 
 - signup/login to netlify 
 - create a project 
 - connect your github account 
 - select the repo. 
 - select the defaults 
 - click on deploy 
 - once deploy, 
 - set environmenables 
 - save 
