# ADFSmartHome
APIs, Services and other stuff for SmartHome with MQTT and other funny stuff
For running all services, just run "docker-compose up" in the root directory

## mqttListener

This service listen to your MQTT Server for specific Topic/s
You have to have an .env file in the service directory with values:

* SERVER=Your server IP
* PORT=your server port
* TOPICS=topic or topics divided by comma (topic1,topic2)
* CONNECTION_TIMEOUT= number of seconds for timeout
* KEEP_ALIVE= keep alive number (how long should the connection have to stay alive)
* RESUBSCRIBE= true or false 
* DYNAMODB_TABLE= Your dynamodb table name
* AWS_REGION=your region at AWS eG (eu-central-1)
* AWS_CLIENTID=Your Client ID for the service user
* AWS_CLIENTSECRET= Your client secret