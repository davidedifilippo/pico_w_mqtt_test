# pico_w_mqtt_test
How publish data trough mosquitto broker

Broker test.mosquitto.org
topic "arduino/simple"

mqtt subscribe --hostname  test.mosquitto.org -p 1883 -t "arduino/simple"
