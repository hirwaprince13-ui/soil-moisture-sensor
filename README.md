# soil-moisture-sensor
component used
________________
-red LED
-green LED
-jumper wires
-soil moisture sensor
-breadboard
-arduino uno
-resistor(2)

description
-------------
This project uses an Arduino Uno and a soil moisture sensor to monitor soil conditions. When the soil is dry, a red LED turns on; when the soil is wet, a green LED turns on. The system is designed and simulated using Tinkercad.
Block diagram used
-------------------
        +-------------------+
        |   Power Supply    |
        |     (5V USB)      |
        +---------+---------+
                  |
                  v
        +-------------------+
        |   Arduino UNO     |
        | (Microcontroller) |
        +----+---------+----+
             |         |
     Analog Input   Digital Output
        (A0)        (Pin 8 & 9)
             |         |
             v         v
   +----------------+  +----------------+
   | Soil Moisture |  |   Green LED    |
   |    Sensor     |  |   (Pin 8)      |
   +----------------+  +----------------+
                         |
                         v
                  +----------------+
                  |    Red LED     |
                  |   (Pin 9)      |
                  +----------------+
