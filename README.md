# airco2ntrold

airco2ntrold is a simple tool to read values from a TFA Dostmann 'AirCO2ntrol Mini' CO2 monitor and publish them using MQTT.

## Alpha install instructions

*This software is currently in alpha state and only serves for testing purpose. Because of that there are many hardcoded parameters which make it very user-unfriendly. All code and documentation are subject to change.*

1. pip paho-mqtt
2. cd /usr/local
3. git clone https://github.com/fablabnbg/airco2ntrold.git
4. cd airco2ntrold/
5. ln -s /usr/local/airco2ntrold/airco2ntrol /etc/init.d/aircon2troldd
6. chmod +x airco2ntrold*
7. update-rc.d airco2ntrold defaults
