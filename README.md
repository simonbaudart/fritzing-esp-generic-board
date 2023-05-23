# Esp Generic Board
The goal of this project is to build a PCB that exposes some of the generic output of a ESP32 DevKit on a PCB of 8 * 8cm

## Inputs
### Power Supply
You can power the board from :
- A AC-DC converter with format HLK-PMxx, like this one : https://amzn.to/3MS7B2v
  - You have to put the jumper Jin on 3.3V or 5V depending of the power supply
  - I suggest to power with 5V to ensure max output

## Outputs
## GPIO
### GPIO1
The GPIO 1 expose the GPIO 18 and 19, with ground and 3.3V on top of the board, with connectors like this : https://amzn.to/3OtbCLU
### GPIO2, 3, 4
The GPIO 2, 3 and 3 expose the GPIO 23,25,26,27,32 and 33, with ground and V on the right of the board, with connectors like this : https://amzn.to/3OtbCLU
To select the output voltage for the V pin, you can use the jumper Jout           

## UART
The uart is exposed on top right of the board with connecter like this : https://amzn.to/3IvOrMX

## I2C
The I2C ports are exposed on top of the board, with connectors like this : https://amzn.to/3OtbCLU
