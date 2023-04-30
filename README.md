# Multithreaded-Client-Server-Chat-Application
Multithreaded client-server messaging application for Sheffield Hallam University Student Community

## Contents of Folder

Supplements folder contain following files
- readme.txt
- Jars (containing the Jars file for Json)
- 1234.txt (containing the backup of the chat)
- Server
- Client

## Commands to run

- Firstly delete the .classpath file in the folder

- Then open the Eclipse and then choose the workspace where you have extracted the folder

- After the Eclipse is open in your workspace, follow the following steps

		1) Go to the 'File' option on the top of menu
		2) Click on the 'Open project from File System'
		3) Click on the Directory and then choose your folder
		4) Project will be successfully opened in your eclipse

- Now, open the Server Package and then right click on the server.java and run it as java application

- After the Server is sucessfully run,  Go to the Client Package and then click on the client.java and 
   run it as java application

- For running the multiple clients, you can run the client.java multiple times


 ## Features Implemented for Client 

- I have implemented the Chat searching extension for the client, in which the client acan serach for any keyword and all 
the chat that are closely related to the keyword will be shown 

- Multiple Client can communicate with each other on the same port and can response to each other


 ## Features Implemented for Server

- I have also implemented the persistence extension for the server.
- Server should be able to back up messages to a persistence storage on local staorge in a file on the disk 
