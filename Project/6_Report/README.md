#  Abstract
  * The Basic Idea behind the design of "SMART IRRIGATION SYSTEM" project was based on the requirement to save water. Different soils and environment required different amount of water. This was the key idea considered for this project. Soil Sensor is used to detect humidity in the soil. As the humidity level goes below the required level it indicates the controller to start the water pump.
---
# 5Ws and 1H

## What
* Smart Irrigation System with Soil sensor and water pump connected to provide water supply when needed.
---
## Where
* Designed to detect soil properties in farm lands, green houses and nurseries.
---
## When
* When the humidity level of the soil goes below the required level the circuit is triggered.
---
## Who
* Required for farmers and botanist.
---
## Why
* To save water from being wasted or to be used water wisely whenever required.
---
## How
* Soil sensor triggers the circuit as the humidity level goes below the required level.
--- 

# SWOT Analysis

| Strengths | Weakness | Opportunity | Threat |
|-----------|----------|-------------|--------|
| No human Intervention is required | System does not work with respect to weather prediction. | System can be installed in farm lands and Green Houses. | No scope to handle the system remotely if any error occured. | 

---

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
  * To operate a DC Water Pump, relays and motor drivers are used.
 
---
## GPIO used

* ### 16x2 LCD display
  * A 16x2 LCD display (Hd44780-9) is used to display the continue reading from the soil sensor.

---
## Microcontroller used

* ### Arduino UNO Board
  * Arduino UNO board is used for all the computing process, which uses ATMEGA 328 microcontroller(uc). It is a 16 Pin microcontroller with inbuilt Aanalog to digital conversion capability. It controlls the 16x2 LCD display and operates the water pump as per the signal received from the soil sensor.

---

# Design
---
  ##  Block Diagram
  
  * High Level Block Diagram
    
    ![Irrigation_block_diagram](https://user-images.githubusercontent.com/98866279/155755529-fe461b8d-7b0a-4676-8bbe-802445b316c3.jpg)

    

    
    * Low Level Block Diagram
    ![Low Level Irrigation](https://user-images.githubusercontent.com/98866279/155824133-0ed2be02-43d9-4cf7-9caf-926f06213bd3.jpg)

 ---
  ## Flow Chart
  
 ![Flowchart_Irrigation](https://user-images.githubusercontent.com/98866279/155825983-717cf916-6def-4141-9852-e2568425aacd.jpg)

 ---


    

