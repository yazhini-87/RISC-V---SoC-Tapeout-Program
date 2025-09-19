# WHOLE FLOW OF SoC Tapeout program
## 1.Chip modeling 
 - (i) GCC
 - (ii) specs(model) - Verification to freeze on specification.
## 2. RTL Architecture 
### Making a soft copy of the hardware using RTL ( Verilog or similar to verilog like chisle ).
 The code gets seperated to 
 - (i) processor (synthesis p1) - gate model without any issue 
 - (ii) peripherals I/Ps
   - macro (synthesis RTL) - synthesis gate like OR , AND etc..
   - analog IPs(function RTL) - logic transistor like MOSFET.
## 3.SoC integration  
connecting all the GPIOs by SoC engineer 
## 4. fabrication 
- GDS-II = DRC/LVS checks = Factory (tape out) = chip
- chip + peripherals

### All these processes output should be equal and checked if it is equal in each steps. 
 

