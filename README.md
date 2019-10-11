# movies-rest-api
REST API build using NODE JS.





Please follow the steps mentioned below to host the REST API in your local:

1. Make sure to install the following softwares mentioned below

    Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.
    Download Url : https://nodejs.org/en/
    
    Visual Studio Code: Code Editor (OPTIONAL).
    Download Url : https://code.visualstudio.com/
	
2. A SQL Server is essential to perform the database operations

3. Clone the repository to your local and run the following command in the project folder to install the node modules

     npm install

4. Update the configuration properties mentioned below in the config/default.json file

    port: 8080 (Port number to host the REST API)<br/>
    databaseServerName: SQL Database server name<br/>
    databaseName: SQL Database name<br/>
    databaseUserId: SQL Database User ID<br/>
    databasePassword: SQL Database Password<br/>
    jwtPrivateKey: Private key to encrypt the user info at the time of Login<br/>
  
5. Run the following command to start the application.

     node index.js
	 

