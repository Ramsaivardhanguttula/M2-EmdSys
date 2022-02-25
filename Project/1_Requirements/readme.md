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
## SWOT Analysis
![Web_Photo_Editor (2)](https://user-images.githubusercontent.com/98812447/155584058-d9bd402c-6692-41ce-b7bb-629a03c9f6af.jpg)
## 5W's and 1H


![5wsand1H](https://user-images.githubusercontent.com/98812447/155658285-72cc0e0c-b3f5-422c-a917-b059019a866b.png)
