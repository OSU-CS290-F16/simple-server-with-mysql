# Simple Dynamic Content Server using Express and Handlebars

This repo contains a basic Express-based server in `server.js` that demonstrates how to serve dynamic content using Handlebars.  Before doing anything with it you need to install dependencies:
```
npm install
```

Then, you can start the server:
```
npm start
```
This will start the server running on port 3000 by default.  You can change the port it runs on by setting the `PORT` environment variable.  Once the server is running, you can visit it at [http://localhost:3000](http://localhost:3000).

## Initializing the database

This repo includes a file `db.sql` that you can use to initialize a database to work with this app.  From a machine with `mysql` installed, you can run this command to import the info from `db.sql` into your database:
```
mysql -h <MYSQL_HOSTNAME> -u <MYSQL_USERNAME> -p <MYSQL_DB_NAME> < db.sql
```
