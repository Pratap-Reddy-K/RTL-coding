
<h1> Problem Statements </h1>

```````

1.Create a module for the given conditions you can connect the 
  wire to a module by 2 ways by position or by name
  
2.You are given a module named mod_a that has 2 outputs and 4 inputs, in 
  that order. You must connect the 6 ports by position to your top-level 
  module's ports out1, out2, a, b, c, and d, in that order.
  
3.You are given a module named mod_a that has 2 outputs and 4 inputs, in 
  some order. You must connect the 6 ports by name to your top-level module's ports
  
4.You are given a module my_dff(that implements a D flip-flop). Instantiate three of them,
  then chain them together to make a shift register of length 3. The clk port needs to be 
  connected to all instances.  
  
5.You are given a module my_dff8(that implements a set of 8 D flip-flops). Instantiate three 
  of them, then chain them together to make a 8-bit wide shift register of length 3.
  
6.Given a module add16 that performs a 16-bit addition. Instantiate two of them to create a 32-bit adder.
  One add16 module computes the lower 16 bits of the addition result, while the second add16 module computes
  the upper 16 bits of the result, after receiving the carry-out from the first adder.

7.Create a circuit with two levels of hierarchy. Your top_module will instantiate two copies of add16 (provided),
  each of which will instantiate 16 copies of add1 (which you must write).
  
8.Provided with the same module add16 as the previous exercise, which adds two 16-bit numbers with carry-in and 
  produces a carry-out and 16-bit sum. You must instantiate three of these to build the carry-select adder, using 
  your own 16-bit 2-to-1 multiplexer.Connect the modules together as shown in the diagram
  
9.Build the adder-subtractor You are provided with a 16-bit adder module, which you need to instantiate twice:
  module add16 ( input[15:0] a, input[15:0] b, input cin, output[15:0] sum, output cout );
  Use a 32-bit wide XOR gate to invert the b input whenever sub is 1.
  
