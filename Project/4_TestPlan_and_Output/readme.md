
## 5_Test plan and Output
   ### 5.1 High level test plan
   | Test ID | Description | Input | Expected output | Actual Output | Passed or not |
| --- | --- | --- | --- | --- | --- |
| 01 | LCD display | Water level in the tank  | Should Display the water percentage and motor state| Display the water % and motor state  |  ✅ |
| 02 | Sense the water level | Water level in the tank  | Should sense the water | Water Level is Detected  |  ✅ |
| 03 | Level Indicator | Water level detected by ultrasic sensor | Water level should be indicated |  Water level is indicated in % |   ✅ |
| 04 | Motor controlling |Water level in % | Shall Switch on and off automatically  | Motor switches on when water level is low and switch off when level is high | ✅ |

   
   
   ### 5.2 Low level test plan
| Test ID (for LCD display)| Description | Input | Expected output | Actual Output | passed/not |   
| --- | --- | --- | --- | --- | --- |
| 01 | Water level percentage | Water level | water is at 0% State of motor |  water is at 0%  Motor is on | ✅ |
| 02 | Water level percentage | Water level | water is at 1% State of motor|  water is at 1% Motor is on | ✅ |
| . | . | . | . |  . | ✅ |
| . | . | . | . |  . | ✅ |
| 26 | Water level percentage | Water level | water is at 25% State of motor |  water is at 25%    Motor is off | ✅ |
| . | . | . | . |  . | ✅ |
| 100 | Water level percentage | Water level | water is at 99% State of motor |  water is at 99%  Motor is off| ✅ |
| 101 | Water level percentage | Water level | water is at 100% State of motor|  water is at 100%  Motor is off| ✅ |


| Test ID (for Motor)| Description | Input | Expected output | Actual Output | passed/not |   
| --- | --- | --- | --- | --- | --- |
| 01 | Motor state | Water level=0 | Motor shall start |  Motor starts | ✅ |
| 02 | Motor state | Water level=1 | Motor shall start |  Motor starts | ✅ |
| . | . | . | . |  . | ✅ |
| . | . | . | . |  . | ✅ |
| . | . | . | . |  . | ✅ |
| 101 |Motor state | Water level=100 | Motor shall stop|  Motor stops| ✅ |
