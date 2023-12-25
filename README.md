# ATMega-328P-Motor-Driver-Board

Quick view of ATMega 328P based 4c Channel Motor Driver board rated at 5V and powered either via a Mini USB connector or solder pads.

8 X Logic Input and 2 X +5V pads and that can accomodate standard 2.54mm dupont header or direct soldering of wiring

# Logic inputs

* D12 : [PB4]
* D8  : [PB0]
* D2  : [PD2]
* A1  : [PC1]
* A2  : [PC2]
* A3  : [PC3]
* A4  : [PC4]
* A5  : [PC5]

# MOTOR CAPABILITIES

All 4 motor outputs can be prgrammed to run Forward or Reverse with M1, M2 and M4 utilising PWM outputs for variable speed settings.

The board measures at approximately 28mm X 43mm.

<img width="428" alt="ATMega 328P Driver Board" src="https://github.com/gxdeange/ATMega-328P-Motor-Driver-Board/assets/57690555/136c3b7f-b33e-4f8e-b9b2-1231b9f0e458">

# Motor Input / Output mapping to MCU:

* M1+ : D3 [PD3] - PWM
* M1- : D6 [PD6] - PWM
  
* M2+ : D5 [PD5] - PWM
* M2- : D10 [PB2] - PWM
  
* M3+ : D7 [PD7]
* M3- : D4 [PD4]
  
* M4+ : D9 [PB1] - PWM
* M4- : D11 [PB3] - PWM

# LED OUTPUT

* Yellow LED+ : D13 [PB5]

<img width="953" alt="328P Motor Conns" src="https://github.com/gxdeange/ATMega-328P-Motor-Driver-Board/assets/57690555/9786955a-5d9a-4359-9931-f27c76479d78">
