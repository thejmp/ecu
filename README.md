# Electronic control unit (ECU) ![Image of pistion](Images/piston_sm.png)
This is my ECU project for my senior project at BYUI

## Abstract
The objective of this project is to take a one-cylinder engine that is carbureted and convert it to fuel injection. This involves replacing a mechanical system with a microcontroller that monitors the engine status and reacts accordingly enabling the engine to run. This conversion is needed to increases fuel efficiency, add some sort of boost, decrease environmental impact, etc.

## Materials
[Parts list csv](parts/sinor%20project.csv)

## PCB & Schematic
![PCB Image](PCB%20%26%20schematic/PCB.PNG) ![PCB Image](PCB%20%26%20schematic/PCB_PCB_2020-06-12_10-47-50_2020-06-15_19-19-58.png)

[PDF schematic](PCB%20%26%20schematic/Schematic_ECUs_2020-06-15_18-41-38.pdf)

[BOM](PCB%20%26%20schematic/BOM_ECUs_2020-06-15_18-41-51.csv)

## Requirements:
 - [x] 	Read data from sensors mounted on the engine
 - [x] 	Control devices needed to enable combustion
 - [x] 	Have all support circuits on one soldered breadboard
 - [x] 	Have a protected wiring harness
 - [ ] 	Have a dashboard to display information
 - [ ] 	Engine running at an idle
### Stretch Requirements:
 - [ ]	Have the engine ruing a base tune 
 - [ ]	Add safety sensors like oil level, battery voltage, etc.
 - [ ]	Add auto shutoff if a problem is detected
 - [ ]	Add load on the output shaft
 - [ ]	Add comfort features like drive by wire, and starter
 - [ ]	Add remote monitoring and control
 - [ ]   Have all circuits on custom PCB
