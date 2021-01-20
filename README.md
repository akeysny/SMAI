# SMAI
Smart Mirror AI

Abstract: To design an Advanced Smart Mirror technology which is also known as Magic Mirror that provides the best advanced user interface and the best user experience. Design and Develop three Internet of Things devices and Magic Mirror. Explore the vulnerabilities associated with unsecure MQTT protocol and propose solutions to mitigate possible risks.

-If you place the 'glass' on a dark surface, you will see just a mirror. When you put a light source behind it, you can see thought it. If you put a black page on the monitor, add some widgets on them, they seem to be part of the mirror's reflection. A Smart Mirror is a great example of an IOT device.

-The mirror offers natural mode of interfaction through which users can use and experience the AI chat assistant. The AI has speech recognition and can respond to a variety of commands. Ability to interact with the personal assistant though Google chat assistant that provides the most natural and convinient mode of interaction. Our Smart Mirror is assembled using a one-way mirror, computer monitor using HDMI socket along with HDMI cable, raspberry pi 4, USB microphone and speaker.
![image](https://user-images.githubusercontent.com/69605343/105234810-a9810300-5b39-11eb-800a-ffb023290a20.png)

![image](https://user-images.githubusercontent.com/69605343/105235659-dfbe8280-5b39-11eb-8171-dc7a71d9d70b.png)

All the IOT devices, which include environmental sensor module, gas sensor module, and light control module, were all based on arduino nano programmable board and ESP8266-01 programmable wifi board for communication.
All boards relied on 9V 600mAh rechargeable batteries by EBL and required a LM2596 DC to DC adjustable voltage regulator to bring the voltage down to 5V usable by arduino nano and most sensor.

A DHT11 temperature and humidity sensor was used as a part of an environmental sensor module.

While the BMP180 digital barometric pressure sensor was used for more accurate temperature readings and atmospheric pressure.

Three gas sensors, from left to right, 
●	MQ-2 - Methane, Butane, LPG, smoke sensor
●	MQ-5 - Natural Gas, LPG sensor
●	MQ-7 - Carbon Monoxide sensor

A light control module relied on motion sensor detection sensor for automatic operation and a 30V relay acting as an electrical switch. For demonstrative purposes RGB LED strip was used as a light source.

Other parts, including sliding Single Pole Double Throw switches, PCB boards and jumper wires were used for prototyping and final product.  
