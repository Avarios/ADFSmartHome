# ADFSmartHome
APIs, Services and other stuff for SmartHome with MQTT and other funny stuff

## mqttListener

This service listen to your MQTT Server for specific Topic/s
You have to have an .env file in the service directory with values:

SERVER=Your server IP
PORT=your server port
TOPICS=topic or topics divided by comma (topic1,topic2)
CONNECTION_TIMEOUT= number of seconds for timeout
KEEP_ALIVE= keep alive number (how long should the connection have to stay alive)
RESUBSCRIBE= true or false 