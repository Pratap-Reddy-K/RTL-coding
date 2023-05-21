
<h1> Problem Statements </h1>

```````

1.Build an AND gate using both an assign statement and a combinational always block.

2.Build an XOR gate three ways, using an assign statement, a combinational always block, 
  and a clocked always block. Note that the clocked always block produces a different circuit 
  from the other two: There is a flip-flop so the output is delayed.
  
3.Build a 2-to-1 mux that chooses between a and b. Choose b if both sel_b1 and sel_b2 are true.
  Otherwise, choose a. Do the same twice, once using assign statements and once using a procedural if statement.
  
4.The given code contains incorrect behaviour that creates a latch. Fix the bugs so that you will shut off the 
  computer only if it's really overheated, and stop driving if you've arrived at your destination or you need 
  to refuel.
  
5.Case statements are more convenient than if statements if there are a large number of cases. So, in this exercise,
  create a 6-to-1 multiplexer. When sel is between 0 and 5, choose the corresponding data input. Otherwise, output 0.
  The data inputs and outputs are all 4 bits wide.
  
6.Build a 4-bit priority encoder. For this problem, if none of the input bits are high, output zero. 
  Note that a 4-bit number has 16 possible combinations.
  
7.Build a priority encoder for 8-bit inputs. Given an 8-bit vector, the output should report the first 
  (least significant) bit in the vector that is 1. Report zero if the input vector has no bits that are high.
  
8.Your circuit has one 16-bit input, and four outputs. Build this circuit that recognizes four scancodes and 
  asserts the correct output.
