# Challenge 2 - GoBarber App (Second Node Module)

## Description

You should improve the GoBarber, the app that is being created.
Up to this point, we have already created the scheduling feature and the restriction that prevents the user from scheduling the service for a past moment or that is already busy.

As the second challenge, you should create a session so that the hairdresser can see his daily schedule. Show the user who has scheduled the service and the date/time as well.

## How to test the app

1. Install the project dependencies: `yarn install`;
2. Set a database server and replace the info inside the [database config file](src/config/database.js):

```
dialect: 'db_dialect',
host: 'db_host_address',
username: 'db_user',
password: 'db_password',
database: 'db_name',

```

3. Run the migrations: `npx sequelize db:migrate` to create the tables inside your database;
4. Run the app: `yarn start`;
5. Visit `localhost:3000` and have fun :nerd_face:.

### Skills

NodeJs, Express, Sequelize, Nunjucks, connect-loki, multer.

### Preview
You can preview the project [here](https://www.loom.com/share/3dd0dc2a321f44289bb7d39e2df3aea1).
