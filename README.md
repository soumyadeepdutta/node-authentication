# NodeJS Authentication boiler-plate
NodeJS Authentication API, using Express, JWT & MongoDb

<img src="https://img.shields.io/badge/node-v12.19.0-blue" /> <img src="https://img.shields.io/badge/npm-6.14.8-orange" /> <img src="https://img.shields.io/badge/express-4.17.1-green" />

### Features
1. User model
2. MongoDB as Database
3. JWT Authentication & Authorization

### Usage
Clone this repository

``git clone https://github.com/soumyadeepdutta/node-authentication.git``

Change directory to 'node-authentication'
```console
$cd node-authentication
```
Create a .env (configuration) file here, which includes
```js
PORT = 3000 // the port to be used during development
DB_CONNECT = <your-mongodb-uri>
```
Install the dependencies and start the server
```console
$npm install
$num run start
```
To run in development mode using Nodemon (hot-reload)
```console
$npm run devstart
```

Report bugs <a href="https://github.com/soumyadeepdutta/node-authentication.git/issues">here </a>.
