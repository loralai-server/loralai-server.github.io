# Loralai


## Build

You will need:

* [NodeJS](http://www.nodejs.org) version 8 or higher.
* [grunt](http://gruntjs.com/)
#### Build using the provided script

Run the [build.sh](./build.sh) script.


## Loading the app

Run the [start.sh](./start.sh) script from the build folder.


## Parameters

Create a .env file in the build folder, containing:


	# Setup file
	# Log files

	# all logs
	LORALAI_LOGS =

	# error logs
	LORALAI_ERR_OUTPUT = 

	# one of fatal, error, warn trace, debug, info
	LORALAI_LOGLEVEL = 

	# MongoDB
	# use either the connection string

	LORALAI_MONGODB_RESOURCE = 

	# either each option
	LORALAI_MONGODB_SERVER = 
	LORALAI_MONGODB_USER = 
	LORALAI_MONGODB_PASSWORD = 
	LORALAI_MONGODB_DATABASE = 

	LORALAI_UDP_PACKET_FORWARDER_PORT = 1750
	LORALAI_HTTP_PACKET_PORWARDER_PORT = 

	# set these for https
	LORALAI_HTTP_PACKET_FORWARDER_CA = 
	LORALAI_HTTP_PACKET_FORWARDER_CRT = 
	LORALAI_HTTP_PACKET_FORWARDER_KEY = 

	# Web Server
	LORALAI_WEBSERVER_PORT = 8080

	# set these for https
	LORALAI_WEBSERVER_CA = 
	LORALAI_WEBSERVER_CRT = 
	LORALAI_WEBSERVER_KEY = 

	# jwt secret
	LORALAI_WEBSERVER_JWT_SECRET = secret
	LORALAI_WEBSERVER_JWT_AUDIENCE = 
	LORALAI_WEBSERVER_JWT_ISSUER = 

	# initial admin user
	LORALAI_WEBSERVER_INITIAL_ADMIN_PASSWORD = admin

	# app key
	LORALAI_APP_KEY_LENGTH = 

	# gateway timeout
	LORALAI_OFFLINE_GATEWAY_TIMEOUT = 
