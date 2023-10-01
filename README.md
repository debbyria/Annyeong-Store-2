# Annyeong Store 안녕
Made by Debby Ria dan Ratih Sanjaya Wahyuningrum, assignment for Pair Project in Hacktiv8

## What is Annyeong Store?
Annyeong Store is a web-based application that offers a wide range of products related to K-pop. The product categories provided include Cheering, Accessories, Album, and Fashion. We use jQuery or EJS with database using Sequelize and Postgresql.

## Tech Stack
For the server side (Backend) we use `Express JS` and for the database we use `Sequelize` and `PostgreSQL`. For the client side (Frontend) we use `EJS`

## Project Setup

```sh
- npm install
- npx sequelize-cli db:create
- npx sequelize-cli db:migrate
- npx sequelize-cli db:seed:all
```

### Compile and Hot-Reload for Development

```sh
nodemon app.js
```

### Notes

> Users must be registered members in order to view the products.