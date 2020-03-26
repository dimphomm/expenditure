# expenditure
 Trace expenses

1. Create a new mysql database named expenses and navigate to Expenses\expenses-server\app\config and open the file db.config.js, edit your database name, user and password accordingly. Note that when you run the project, database tables will be generated automatically if not exist using migration.
2. Using command line, navigate to expenses-server folder and run the command node server.js
3. From 2 above, the server side will be running and waiting for client requests. 
4. Open another command line and navigate to expenses-client folder and run the command ng serve --port 8081. The client side will be listening on port 8081 and can be access using the url http://localhost:8081/ if run on localhost.
