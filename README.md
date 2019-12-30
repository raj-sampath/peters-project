# peters-project
Starter Project for Peter

Epic - Create and host a server to respond to incoming requests
	User Story 1 - Create a Server
		Task 1 - Choose a comfortable coding language which has frameworks avaliable to setup servers easily. Eg Java, .Net, NodeJs, Python, GoLang, RubyOnRails, Php
		Task 2 - Set up a local server to run on LocalHost - 127.0.0.1
		Task 3 - Setup a URL Path /record (127.0.0.1/record)
		Task 4 - On Navigating to the URL 127.0.0.1/record the following message should be displayed
					Your IP is xx.xx.xx.xx

	User Story 2 - Setup Database
		Task 1 - Chosse any database set up a local instance for it. MySQL and MongoDB are good open soure databases to get started with.
		Task 2 - Using the ORM in the framework chosen in the above the User Story, create a connection between the server code and the database.
		Task 3 - Setup a DB Object to store the IP. The DB object should have the following structure
				1. Primary Key ID
				2. IP
				3. Date Recieved
		Task 4 - Setup a Calss using the ORM for the above mentioned structure.
	
	User Store 3 - Putting it together
		Task 1 - Setup a Contorller to Accept a request that appears on /record and records the IP of the.
		Task 2 - A Object is created with this IP and saved.
		Task 3 - On Object Save then send the response menioned on Task 4 of User Story 1.
