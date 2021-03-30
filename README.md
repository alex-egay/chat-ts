# Chat on Docker, Mongo, React, Typescript

## Requirements

-  Docker
-  Yarn/npm

## Development
### Install dependencies
```bash
cd ./api
yarn
cd ../client
yarn
cd ..
```
### Configure the environments
   Copy the `.env.example` from `api` to `.env.production`
   
   Copy the `.env.example` from `client` to `.env.production` & `.env.development`
##Run   
```bash
yarn start
```
### Docker
```bash
docker-compose up --build
```
