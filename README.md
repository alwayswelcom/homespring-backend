Backend for [Homespring Test](https://rebootinvesting.com/)
===========

This project is to getting data from OAuth api with Book store based on Nust.js(Node.js frameworks)


Installation
------------

First of all, download and install the [node.js](https://nodejs.org/en/download/) on your PC

## Git clone
  
   Use the following command in terminal.
   ```sh
   git clone https://github.com/alwayswelcom/homespring-backend.git   
   cd homespring-backend
   ```

 ## Installation

```bash
$ npm install
```

## Running the app

On local, creat .env file and write down
```bash
GOOGLE_API=https://www.googleapis.com/books/v1
```

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```sh
# unit tests
$ npm run test
```
You could check the backend status on `localhost:8000`
