# E-commerce Back End

## Description
The e-commerce backend is a backend setup for an e-commerce application. It uses an Express.js API and Sequelize to connect to a MySQL database. When the database is created and seeded with test data, the server can be started and the Sequelize models are synced to the database. The GET, POST, PUT, and DELETE API routes can then be used to access the data in the database.

## Usage
Install dependencies:

```
npm install
```

Create a `.env` file in the root directory. Within this file, specify the database name, your username, and your password. Like this:

```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='myPassword'
```
Then seed the database:

```
npm run seed
```

Start the server with:

```
npm start
```


