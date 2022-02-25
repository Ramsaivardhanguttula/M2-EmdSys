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
Microprocessor acts as the brain of the  **AUTOMATIC WATER FILLER AND WATER LEVEL INDICATOR** project. It takes informatio from the ultrasonic sensor, gives commands to the LCD display, relay and motor.
## SWOT Analysis
![Web_Photo_Editor (2)](https://user-images.githubusercontent.com/98812447/155584058-d9bd402c-6692-41ce-b7bb-629a03c9f6af.jpg)
## 5W's and 1H


![5wsand1H](https://user-images.githubusercontent.com/98812447/155658285-72cc0e0c-b3f5-422c-a917-b059019a866b.png)

## Requirements

<!-- Tables -->
### High Level Requirements

| ID | High Level Requirements |
| -------- | -------------- |
| HL1 | It shall fill the water tank automatically |
| HL2 | It shall indicate the water level in the tank |
| HL3 | It shall automatically turn off the motor when the tank is filled |
| HL4 | It should display at what level the water is present  |

### Low Level Requirements

| ID | Low Level Requirements for HL1|       |ID | Low Level Requirements for HL2|
| -------- | -------------- | ---- |-------- | -------------- |
| H1L1 | According to the inputs from the Ultrasonic Sensor the Microcontroller instructs the motor|       |H2L1 |  The ultrasonic sensor shall sense the distance between the upper suface of the tank and a particular level where water is present and informs the distance to microcontroller as input  |
| H1L2 | Based on the commands received from the Microcontroller through relay circuit the motor shall fill the tank by turning on itself|       |H2L2 | Based on the value of distance the level shall be indicated through LCD display |



| ID | Low Level Requirements for HL3|  |ID | Low Level Requirements for HL4|
| -------- | -------------- | ---- | -------- | -------------- |
| H3L1 | When the motor gets turned on and water is filling the ultrasonic sensor shall detect the level and at when water reaches particular threshold value it signals the Microprocessor  |  | H4L1 | It shall be able to detect the various distances and provide distance value to the Microcontroller |
| H3L2 | The micro controller should command the relay and turn off motor |  | H4L2 |The microcontroller shall divide the distances to levels and display the particular level in 16*2 LCD display |

---
