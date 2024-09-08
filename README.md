# Garage Door Opener Custom Board for ESP Home 
## Hardware
Hardware consists of an Arduino Nano ESP32, with a 4 channel relay board (2 channels used). Relays are used to close the contact to operate the door.

Pin assignments are as follows:
```
			Small Door		Large Door
			Nano PIN / GPIO		Nano PIN / GPIO
Relay			D2 / 5			A7 / 14
Operate LED (Yellow)	D4 / 7			A5 / 12
Open LED (Green)	D6 / 9			A3 / 4
Closed LED (Red)	D8 / 17			A1 / 2
Sensor (Reed Switch)	D12 / 47		D13 / 48
```
N.B. Sensor is closed circuit when door is closed.
