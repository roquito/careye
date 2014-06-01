careye
======

Arduino code for CarEye: CarEye is a solar-powered device that sits inside your car and calls you to alert you that a baby has been left unattended inside the car.

I used the careye file on an Arduino Uno with a "Ge Tech WGW-06633" GSM shield. For temperature readings, I used a DHT11 sensor and for human detection I used an HC-SR501 Pyroelectric Infrared Human Sensor Module.

In order to read temperature from the temperature sensor, you need to use the DHT11 library available at: 
http://arduino-info.wikispaces.com/DHT11-Humidity-TempSensor
