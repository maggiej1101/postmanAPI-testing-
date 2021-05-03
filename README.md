  Connect to Database​
    1.xmysql, is developed on top of Node.js library. So, first Install Node: https://nodejs.org/en/download/​
    2.Once the installation for Node.js is completed, goto CMD and download xmysql package, using “npm install -g xmysql” command.​
    3. Now, its time to connect to your MySQL DB instance. If you don’t have MySQL, download and install from https://dev.mysql.com/downloads/installer/​
      Use, below command to connect to MySQL​
      xmysql -h localhost -u Username -p Password -d DBName​
      Here, provide your Username, Password and DBName, e.g.​
      xmysql -h localhost -u root -p admin -d TMS​
    4. You should see below screen on the CMD​
    5. This is Optional step, just in-case you encounter with “er_not_supported_auth_mode client does not support authentication protocol” exception, Re- configure Authentication Method f​
    6. All done! You are set to execute this collection in Postman. Just to ensure that everything is working as expected. Send http://localhost:3000/_version request from Postman. It should return installed version of Xmysql, mysql and node.or MySQL, there you select legacy type password support for 5.1​
    7. Let us fetch the list of all rows of table.​
      
