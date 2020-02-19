# IoT demo with Raspberry Pi
A demonstration of connecting DHT11 sensor, RGB LED and a DC motor to Raspberry Pi and controlling them using AWS IoT 
## dht11_read_and_publish.py
A script that reads data from a DHT11 sensor and publishes to AWS IoT
## led_motor_switch.py
A script that acts like a switch that changes the AWS Device Shadow state of a device 
## led_motor_controller.py
A script that subscribes and publishes to an AWS Device Shadow topics and changes the state of a device.
Run this script prior to led_motor_switch.py
