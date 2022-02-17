# Tiny LED Card
 A tiny credit card sized LED light
 
 <img src="/Pictures/alu-led-pcb.jpg" width="400">

# Hardware
 Currently using 3030 LED and TPS61165 driver.
 Update 2022 Feb: It seems that you can't buy the TPS61165 anymore, all places are out of stock. 

## 3030 LED
 Luminus Device MP3030-110H
 
 Nominal: 3V 65mA
 
 Maximum: 200mA

## TPS61165
 Boost converter for LEDs in series

 Input voltage: 3-18V
 
 1.2A current limit

## PCB
 Aluminium PCB, single layer, for LED.
 
 FR-4 PCB, Two layers, for driver.
 Components on single side for easy assembly.
 
 2 PCBs connected with 2.54mm headers for upgradability 

## Enclosure
 3D Printed with PLA or any filament
 
 Screws: 4x M3x20
 
 2x M3x12-16mm 
 
# Assembly
 See the BOM for parts.
 Total cost should be under $25

 For the Aluminium PCB, you need a hotplate or a beefy hotair gun.
 It is impossible to solder with a soldering iron 
 
 For the driver PCB, any soldering iron will work, hotplate would also work well.
 
 R1 and R2 are the sense resistor for the LED driver, use the following resistor: 
  for other current see the datasheet of TPS61165
 
 | Resistor (Ω)  | LED Current (each) | Power | 
| ------------- | ------------- | ------------- |
| 1  | 50mA  | 14.4W |
| 0.5  | 100mA  | 28.8W |
| 0.33  | 150mA  | 43.2W |
| 0.25  | 200mA  | 57.6W |

 For the enclosure, print each file once and screw them together.
 
 Glue a heatsink with thermal adhesive at the back of the aluminium PCB after checked working.

## Usage
 Plug a 12V DC power supply in, light will come out from the bright side.
 
 It is not advised to use the Micro USB for power as a large amperage will be needed at 5V. Also, having both accidentally plugged in will damage the Micro USB device.
