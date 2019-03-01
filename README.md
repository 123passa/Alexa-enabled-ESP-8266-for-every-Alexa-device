# Alexa-enabled-ESP-8266-for-every-Alexa-device
This code will help you creating a smart home accessory starting from an ESP-8266 usualy commercialized as NodeMcu. 


The code is a modification of the one in this guide https://www.instructables.com/id/Control-Your-Projects-With-Google-Assistant-and-Ad/


The guide is meant to be for super noobs in order to help you out if you have a Sonos or an echo after the first generation.

What I will suggest you is to follow almost everything in the guide linked above. You should modify few things and use my code.

The pints of the guide that needs to be modified are the following:

1. Instead of adding a switch add a text block
2. Load the code I provided you into the ESP and change the following:
    #define WIFI_SSID "HERE ADD YOUR WIFI NAMe"  
    #define WIFI_PASS "HERE ADD YOUR WIFI PASSWORD"  
   
    #define MQTT_NAME "HERE ADD YOUR ADAFRUIT IO USERNAME (YOU CAN FIND IT CLICKING THE YELLOW KEY ON YOUR ADAFRUIT DASHBOARD)" 
    #define MQTT_PASS "HERE ADD YOUR ADAFRUIT IO ACTIVE KEY NAME (YOU CAN FIND IT CLICKING THE YELLOW KEY ON YOUR ADAFRUIT DASHBOARD)"
 
 3. The applet part is almost the same but obviously you need to create them with Alexa. In the case is not clear how to do so please ask me, on this git hub page, i take few time to answer. 
 3. if you are interested I added a blink feature you need to build an applet that is gonna give a BLINK command to adafruit
 
 Notice that you will need to say "Alexa trigger light on" "Alexa trigger light off" "Alexa trigger light blink" and not just "Alexa turn light on"
