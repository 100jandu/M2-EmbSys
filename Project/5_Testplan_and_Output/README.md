
# Test plan and output

#### Test plan is created and verified on both manual and automated manner
---
## HIGH LEVEL TEST PLAN / Integrated test plan

| Test ID | Description | Input | Expected output | Actual Output |
| --- | --- | --- | --- | --- |
| 01 | Soil Sensor | Water into soil | Resistance |  ✓ |
| 02 | Relay | Analog input(Resistance value) | To start the water pump | ✓ |

| Test ID | Description | Input | Expected output | Actual Output |
| --- | --- | --- | --- | --- |
| 01 | Soil sensor | Humidity reading from soil  | Resistance value upto 1Kohm | ✓ |
| 02 | LCD display | Data from Board | Display status of the soil sensor |  ✓ |
| 03 | LCD display | Data from Board | Display status of the water pump |  ✓ |

---

## LOW LEVEL TEST PLAN / Unit test plan

| Test ID (for soil sensor)| Description | Input | Expected output | Actual Output | passed/not |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for Soil Sensor | Humidity | Less amount of water |  Value greater than 400ohm | ✓ |
| 02 | Check for Soil Sensor | Humidity | Ample amount of water |  Value less than 400ohm | ✓ |

| Test ID (for relay)| Description | Input | Expected output | Actual Output | passed/not |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for Relay | Resistance value | Value greater than 400ohm | Strats the water pump | ✓ |
| 02 | Check for Relay | Resistance value | Value less than 400ohm |  Stops the water pump | ✓ |

| Test ID (for Interrupt Pin)| Description | Input | Expected output | Actual Output | passed/not |
| --- | --- | --- | --- | --- | --- |
| 01 | Check for Interrupt Pin read| Restrict the controller from the continous monitoring of the reading from soil sensor | Input from soil sensor |  Resistance reading to the controller | To be done |


---
