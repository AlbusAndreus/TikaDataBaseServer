# TikaDataBaseServer
The server program that receives data from the client program and puts it into a database for  cataloging
This program put metadata sent from the client program into the database. This will not work with any database. It was made to work on a Macbook Pro and was able to connect with the client program running on the same machine. This program utilizes SQLite3 and the JDBC connector to write to the database using SQL commands embedded in Java. It catalouges video file metadata, but that is just for testing the working model of this program.
