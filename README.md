# Configuration-retrieval

This project consists of a React front-end server and a Flask back-end server. The front-end server sends requests to the back-end server at any of the three endpoints. When requests are sent to these endpoints after clicking a button in the front-end server, the response is the configuration information in JSON pertaining to each of these endpoints. This configuration information is generated from the output of three different Linux commands where each command is specific to one endpoint. When the responses are sent from the back-end server to the front-end server, the back-end server works to store the responses in an SQL database. This database is accessed through MySQL and consists of 3 tables that correspond to each endpoint. The exact date and time the responses get generated is kept track of so that each record in the SQL table is unique on top of making it easier to find changes regarding the system configuration that can cause errors that prevent an application from running normally.
