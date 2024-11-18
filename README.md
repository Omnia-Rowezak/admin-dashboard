## MERN + Antd Stack Admin Dashboard

## Installation

### Backend
1) just create MongoDB Atlas account database url 
2) change this file name .variables.env.tmp to  .variables.env
3) open  .variables.env and paste your MongoDB url here :  DATABASE=your-mongodb-url
4) npm install
5) npm setup
6) npm start

## Frontend
1) cd frontend 
2) npm install
3) change api config to localhost in this : src/frontend/src/config/serverApiConfig.js
4) cd frontend
5) npm start
 
```

## App Features :

### Backend :

* The backend is built with node.js , [express.js Framework](https://expressjs.com/) ,and MongoDb Database
* Generic Crud Api (Create / Read / Update / Delete)
* Admin (User) Management Api
* Auth by Jwt json web token

### Frontend :

* The Frontend is built with React.js , [Ant Design (Antd)](https://ant.design/), and Redux , Redux-thunk.
* Generic Crud Component (Module) (Create / Read / Update / Delete)
* Admin (User) Management Module
* Auth Component Login / Logout
* Private Route and Public Route
* Not Found Page
* Beautiful UI Dashboard
```