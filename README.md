# IoT demo with Raspberry Pi
A demonstration of connecting DHT11 sensor, RGB LED and a DC motor to Raspberry Pi and controlling them using AWS IoT 
# dht11_read_and_publish.py
Python script thata reads data from DHT11 sensor and published it to AWS IoT
# led_motor_switch.py
Python script that acts like a switch which chnages the an AWS Device Shadow state of device. 
# led_motor_controller.py
Python script that subscribes and publishes to an AWS Device Shadow topics and changes the state of a device.
Run this script prior to led_motor_switch.py
