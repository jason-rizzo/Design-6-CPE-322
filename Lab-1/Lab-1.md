# CPE 322 - Lab 1 
## GHDL and GTKWave 
--- 
### Installation 

Following the instructions for installing the GHDL and GTKWave software functioned as intended, as both pieces of software were downloaded, extracted, and placed in the proper folders to function. After these instructions were completed, a Windows command utility was opened, and the programs' executable files were invoked through the command line to run the two examples. 

### Part 1: Half Adder Example 

The first set of files to be tested was the Half Adder example, which included ha.vhdl and ha_tb.vhdl. These files model and test a simple half adder component by modifying the values of the input signals. The signals a and b are used as inputs, and the output signals, s and c, are generated using the standard function of a half adder, in which s takes the value of a XOR b, while c takes the value of a AND b. 

The proper GHDL commands were invoked via the command line to run the simulation test bench for this half adder and generate the output wave signal file. 

![GHDL Commands for the Half Adder Example](Lab_1_Part_1_Terminal.png) 

The test bench modified the values of the inputs to fully test the system, and the responses through the output signals were simulated as a result. The generated waveforms demonstrated these results, which make sense based on the description of a standard half adder. They were displayed in GTKWave using the command line, similarly to the usage of GHDL. 

![GTKWave Output for the Half Adder Example](Lab_1_Part_1_Wave.png) 

The signals all begin undefined, but when a and b are set to 0, s and c are also 0. When only b is set to 1, s becomes 1, and when only a is set to 1, s is also 1. By setting both a and b to 1, s becomes 0 again, with c becoming 1. This matches the implementation of a half adder, as c is only 1 when a and b are 1, while s is only 1 when either a or b are 1, but not both. 

### Part 2: D Flip-Flop Example 

The second set of files to be tested was the D Flip-Flop Example, which included dff.vhdl and dff_tb.vhdl. These files model and test a basic D flip-flop, similar to the basic half adder in the Half Adder Example. the signals clk, din, and rst are inputs, while dout is an output. The output, dout, becomes 0 if rst is 1, and otherwise, it takes the value of din when clk reaches its rising edge. 

The same GHDL commands were invoked again on the new files, and the simulation test bench produced an output wave signal file. 

![GHDL Commands for the D Flip-Flop Example](Lab_1_Part_2_Terminal.png) 

The test bench oscillated the value of clk every 5 ns, and modified the values of rst and din. The value of rst being 1 initially did not change dout, as it was already 0, but with rst set to 0 and din set to 1, the next time clk changed from 0 to 1 caused dout to become 1, but dout then became 0 again after rst became 1, regardless of the value of din. This output signal was visualized in GTKWave, exactly as in the Half Adder example. 

![GTKWave Output for the Half Adder Example](Lab_1_Part_1_Wave.png) 

Both of these examples were simulated and displayed correctly, and the behavior of each modeled component made sense based on their theoretical descriptions. 

