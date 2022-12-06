# mechanics_rpm_mesure_tool
The simple device based on arduino that will allow using an hall sensor a3144 to mesure how many RPM gear do.
# Schematic:
The schematic is easy is just 2 resistors and A3144 and one led:
![image](https://user-images.githubusercontent.com/20460747/205875397-4060d0ce-d347-449f-8a3f-94528122093f.png)
# BOM list:  
  1. 1x Arduino Nano 
  2. 2x 1KOm resistors
  3. 1x A3144 sensor
  4. 1x Breadboard
# Software 
There are two softwares released. First is Arduino IDE code that is uploaded to Arduino. This code read value from sensor and returns rpm or time is can be configured in firmware defines. The second software is CLI tool that plots an data like graph and saves is data.txt file for postproccessing. Written on Rust programming language.
# Demo
![image](https://user-images.githubusercontent.com/20460747/205876439-df42d0a4-aea0-484f-ba7e-c943ae642ee8.png)
# device apperance:
I used glue to make sure that my wires will be not left chat during an experiment:
![image](https://user-images.githubusercontent.com/20460747/205881930-d5dd1d3b-f1c6-4ead-b658-4e7744373b87.png)
![image](https://user-images.githubusercontent.com/20460747/205882062-a6a05c63-23d4-48ca-b495-1558bdcb1dfc.png)
