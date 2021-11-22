Following a Digi-key youtube series. 
This is for video 2: https://youtu.be/gtkQ84Euyww

Discription: modifiy code to change the status of one or more of the LEDs.

instructions for installing your code;

Lattice iCE40 product page (with pinout spreadsheet and datasheet): https://www.latticesemi.com/en/Produc... 

We install the apio tool (https://github.com/FPGAwars/apio), which will help us install and control other lower-level tools required to synthesize, simulate, and upload our FPGA designs:

 - Synthesis: http://yosyshq.net/yosys/
 - Simulation: http://gtkwave.sourceforge.net/ 
 - Place and route: https://github.com/YosysHQ/nextpnr
 - Package: icepack (as part of Project IceStorm: https://github.com/YosysHQ/icestorm)
 - Upload: iceprog (as part of Project IceStorm: https://github.com/YosysHQ/icestorm)

The apio documentation can be found here: https://apiodoc.readthedocs.io/en/sta...