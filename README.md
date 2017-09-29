# usb1_device
USB 1.1 Device IP Core

Description

USB 1.1 slave/device IP core. Default configuration is 6 endpoints: 
1 Control, 1 Isochronous IN, 1, Isochronous Out, 1 Bulk IN, 1 Bulk 
Out, 1 Interrupt IN. Includes control engine, providing full enumeration 
process in hardware - no external micro-controller necessary. 
Derived from my USB 2.0 Function IP core, except all the high speed 
support logic has been ripped out and the interface was changed from 
shared memory to FIFO based. 

A basic test bench is now included as well. It should be viewed 
as a starting point to write a more comprehensive and complete 
test bench. 

I expect the users of this core to have some fundamental USB knowledge 
and be familiar with the UTMI specification and with the general USB 
transceivers (e.g. from philips). If you are not familiar with these two 
you should check out www.usb.org and read up on this subject ...

Features

- USB 1.1 Compliant Function 
- Hardware enumeration support 
- No micro controller/CPU required 
- FIFO based interface 
- Written In Verilog 
- Fully Synthesisable 
- Tested in Hardware
