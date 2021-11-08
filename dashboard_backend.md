<h1 align="center">
<br>
  <img src="https://edteam-media.s3.amazonaws.com/blogs/original/35424907-307f-4ac2-beca-56927027bda2.jpg" alt="MVC" width="450" height="200">
<br>
<br>
Statistics LeishManiasis Dashboard Backend
</h1>

<hr />
<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->


## Description
Backend for Statistics Dashboard. MySQL, Sequelize and Express.

## Table of contents
This project features the following tools:

- :coffee: **Express** — 4.17.1
- :file_folder: **Sequelize**

## Installation and Hands On
1. Clone this repo using `https://github.com/MegaProyectoUVG/dashboard-leish-backend.git`
2. Move to the appropriate directory: `cd dashboard-leish-backend`.<br />
3. Run `npm install express body-parser dotenv`.
4. Run `npm install --save-dev @types/express @types/body-parser @types/dotenv`.
5. Check your `.env` file for conecting to database in `connection.ts`.
6. Run `nodemon app.ts` command. <br />

## Bulding
1. Run `npm run build`

## Run it on javascript too
1. Run `npm run prod`

## References
### Structure
 - React + Node.js + Express + MySQL CRUD App - https://bezkoder.com/react-node-express-mysql/#Nodejs_Express_Back-end
 - Sequelize API Reference - https://sequelize.org/master/manual/model-basics.html
 - Routing - https://expressjs.com/en/guide/routing.html

### Security
 - Express: cors - https://expressjs.com/en/resources/middleware/cors.html
 - How To Use JSON Web Tokens (JWTs) in Express.js - https://www.digitalocean.com/community/tutorials/nodejs-jwt-expressjs
 - express-basic-auth - https://www.npmjs.com/package/express-basic-auth

### Useful lectures
 - How to send the authorization header using Axios - https://flaviocopes.com/axios-send-authorization-header/
 - Web API Authentication Basic vs Bearer - https://stackoverflow.com/questions/34013299/web-api-authentication-basic-vs-bearer

### Continuous Maintenance
 - Logging Node.js applications with Winston and Log4js - https://developer.ibm.com/tutorials/learn-nodejs-winston/
 - npm winston - https://www.npmjs.com/package/winston#transports
 - sequelize logs - https://stackoverflow.com/questions/40374499/how-to-write-sequelize-log-to-a-file-instead-of-console
### Videos
 - Restful API with NodeJS, Express & Typescript - https://www.youtube.com/watch?v=vyz47fUXcxU
 - Authentication with JSON Web Tokens using NodeJS, Express, Typescript & MySQL - https://www.youtube.com/watch?v=LHn7PHN4nv4
 - React + Node.js Express: User Authentication with JWT example - https://bezkoder.com/react-express-authentication-jwt/
 - Front End Part: https://bezkoder.com/react-jwt-auth/
 - Back End Part: https://bezkoder.com/node-js-jwt-authentication-mysql/

### How to test users insertion
`localhost:8080/api/auth/register`
```json
{
  "username": "pancho",
  "email": "pancho@pato.com",
  "password": "pass123",
  "roles": ["admin"]
}
```

`localhost:8080/api/auth/login`
```json
{
  "email": "pancho@pato.com",
  "password": "pass123"
}
```

## License
No license.


