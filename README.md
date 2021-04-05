# SQLite3-Flask-Python-Java
Managing a SQLite3 server with python and flask, INSERT UPDATE DELETE with java app. 


With these programs you are able to maintain a live updated table with variables from Java applets. 

Java applet POST requests to your Python Flask server that is listening, the server then handles the request.

The request address determines which operation INSERT UPDATE DELETE (more can be easily added) the server will perform on a SQLite database. 

The request contents passed as URL string and parsed into a dictionary then into a SQL readable statement. The statements are then automatically executed on the databse. 

This working program will enable Java applets to create an intial record with log variables, then to periodically update these records and on condition delete the intially created record.

