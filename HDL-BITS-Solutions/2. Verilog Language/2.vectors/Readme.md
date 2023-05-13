
<h1> Problem Statement </h1>


```````
1.Build a circuit that has one 3-bit input, then outputs the same vector, 
  and also splits it into three separate 1-bit outputs. Connect output o0 
  to the input vector's position 0, o1 to position 1, etc.
  
2.Build a combinational circuit that splits an input half-word (16 bits, [15:0] )
  into lower [7:0] and upper [15:8] bytes.

3.A 32-bit vector can be viewed as containing 4 bytes (bits [31:24], [23:16], etc.). 
  Build a circuit that will reverse the byte ordering of the 4-byte word.
  AaaaaaaaBbbbbbbbCcccccccDddddddd => DdddddddCcccccccBbbbbbbbAaaaaaaa
  
4.Build a circuit that has two 3-bit inputs that computes the bitwise-OR of the two vectors,
  the logical-OR of the two vectors, and the inverse (NOT) of both vectors. Place the inverse of b in the 
  upper half of out_not 
 ````````
  5.Build a combinational circuit with four inputs, in[3:0].
    There are 3 outputs:
  <u1>
   <li>out_and: output of a 4-input AND gate. </li>
   <li>out_or: output of a 4-input OR gate. </li>
   <li>out_xor: output of a 4-input XOR gate.</li>
  </u1>
  
 `````````
 6.Given several input vectors, concatenate them together then split them up into several output vectors.
   There are six 5-bit input vectors: a, b, c, d, e, and f, for a total of 30 bits of input. There are four 
   8-bit output vectors: w, x, y, and z, for 32 bits of output. The output should be a concatenation of the 
   input vectors followed by two 1 bits.

 7.Given an 8-bit input vector [7:0], reverse its bit ordering.
 
 8.Build a circuit that sign-extends an 8-bit number to 32 bits. This requires a concatenation of 24 copies of 
   the sign bit (i.e., replicate bit[7] 24 times) followed by the 8-bit number itself.
  
 9.Given five 1-bit signals (a, b, c, d, and e), compute all 25 pairwise one-bit comparisons in the 25-bit output vector. 
   The output should be 1 if the two bits being compared are equal.
 
