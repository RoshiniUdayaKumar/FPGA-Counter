# FPGA-Counter
# FPGA-Counter
The first part of this project is simple and straightforward, writing a Verilog code that will use the switches on the FPGA ZYBO Board to turn on and off the LEDs.

The second part of this project is to develop a 4-bit counter. The counting operation is indicated by the LEDs. We are aware of the two counting operations up counting and down counting. Button 0 is used to perform up counting and Button 1 is used to perform down counting.

Finally, we shall design a "Jackpot Game" with the following conditions:
1. The divided clock circuit described might be used in the jackpot game. 
2. When the switch corresponding to that switch's LED is turned on, all the lights should turn on. (and that this condition is called a Jackpot)
3. A reset can be performed by pressing one of the push buttons.

This repo describes the Verilog Code and XDC file. You can also test these functionalities by writing appropriate testbenches. 

Note: All of the FPGA pins that are routed to physical pins on your board are listed in the master XDC file for your board.

The FPGA board used for this project is Digilent Zybo-Z7
