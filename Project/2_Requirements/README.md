# Requirements
---

##  High Level Requirements

| ID | High Level Requirement |
|----|------------------------|
| HLR1 | Land with Fertile soil. |
| HLR2 | Sufficient amount for water supply. | 
| HLR3 | Proper Power Management to save battery life. |

## Low Level Requirements

| ID | Low Level Requirement | Type |
|----|-----------------------|------|
| LLR1 | Soil sensor and DHT11 sensor is required to study the property of the given soil .| HLR1 |
| LLR2 | Motor Drivers and relays are required to start and stop the water pump. | HLR2 |
| LLR3 | 12V battery to provide sufficient power supply. | HLR3 |

---

## Sensor used

* ### Soil Sensor
  * It is an analog sensor used to detect humidity of the soil.
  
---

## Actuator used

* ### Motor
  * To operate a DC Water Pump Relays and Motor and motor drivers are used.
 
---
## GPIO used

* ### 16x2 LCD display
  * A 16x2 LCD display (Hd44780-9) is used to display continue the reading from the soil sensor.

---
## Microcontroller used

* ### Arduino UNO Board
 * Arduino UNO board is used for all the computing process, which uses ATMEGA 328 microcontroller(uc). It is a 16 Pin microcontroller with inbuilt Aanalog to digital conversion capability. It controlls the 16x2 LCD display and operates the water pump as per the signal received from the soil sensor.

