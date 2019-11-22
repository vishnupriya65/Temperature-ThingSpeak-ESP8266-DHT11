# Temperature-Thingspeak-ESP8266-DHT11
  Code for sending temperature sensor data to ThingSpeak cloud platform where you can aggregate, visualize, and analyze live data streams. We use wifi modem NodeMCU and DHT11 will be used to measure the temperature and humidity readings.
  
# Components Required:
    NodeMCU
    DHT11 Temperature and Humidity sensor
    
# Circuit Connections:
    VCC-Vin
    GND-GND
    D2 -Data Out
# Creating a ThingSpeak Account:
    1.Go to https://thingspeak.com/ and Login to your account or create an account if you do not have one.
    2.Click Channel > New Channel. Enter basic details of the channel(Name of your channel and choose field whatever you want).Then scroll down and save the channel.
    3.Now,The channel was updated. Channel ID is the identity of your channel.
    4.To get the API key, Go to Account > My Profile > User API key.
