# Smart Greenhouse mbed Repository

In serial.h, there are functions controling communicate between Mbed and Raspberry Pi. This communication is using serial communications.

In sensors.h, there are classes controling sensors collecting date from greenhouse. Light sensor and Temperature and humidity sensor are using I2C communication. Moisture sensors are using ADC. 

In actuators.h, there are classes controling fan, heater, light, pump and valves. 

In the main.h, combine everything together, and run the greenhouse automatically. Use data collecting from sensors to control these things turn on and off.
