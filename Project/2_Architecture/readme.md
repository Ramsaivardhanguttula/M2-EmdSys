
# AUTOMATIC WATER FILLER AND WATER LEVEL INDICATOR
## Description
The name of the project is **AUTOMATIC WATER FILLER AND WATER LEVEL INDICATOR** which is an innovative and efficient idea, which fills the water tank automatically and also indicates the water level. In this project the tank will be divided into certain levels and the level will be indicated in LCD display. Whenever water decreases to a certain threshold the motor gets automatically switched on and the water will be filled to certain level and turns off automatically.
## Block diagram
![AutomaticWaterFillerAndWaterLevelIndicator](https://user-images.githubusercontent.com/98812447/155518159-00aaa8de-ee56-4e4e-bc10-a3925db845ed.png)
### Sensor(Ultrasonic Sensor)
As the name indicates, ultrasonic sensors measure distance by using ultrasonic waves. The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. The ultrasonic waves emitted hits the water and the distance is measured. This information is given to the microprocessor as input.
### LCD display
* 16×2 LCD is a 32 digits display screen for all kinds of CMOS/TTL devices. This word comes from the liquid crystal and 16X2 represents its screen size. In Liquid crystal display 16×2, there are 2 rows and 16 columns. 
* In this project LCD display is used to provide the information by indicating the water level, the state of the motor, the height data can be visualized
in the LCD 16 × 2 display. The LCD displays the real-time data of the water height in the water tank. This takes input from the microprocessor.
### Relay
*  A relay is electro mechanical switch which is controlled electrically. It is used for isolation of two circuits having different operating voltages.
*  Relay in this project energises the motor when the water level is below the threshold and de-energises the motor when water level reaches a certain level.
### Driver circuit
A relay driver circuit is a circuit which can drive, or operate, a relay so that it can function appropriately in a circuit.
### Memory

### Actuator(Motor)
Motor is used in his project to fill the tank with water according to the instructions given by the microprocessor. It is connected to a relay which energises and de-energises based on the water requirement.
### MicroController
Microprocessor acts as the brain of the  **AUTOMATIC WATER FILLER AND WATER LEVEL INDICATOR** project. It takes informatio from the ultrasonic sensor, gives commands to the LCD display, relay and motor
