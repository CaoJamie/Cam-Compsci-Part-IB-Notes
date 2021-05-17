# Computer Design

## Verilog

This is in fact, more of ECAD Practical lab's content. But this was also included in the exam paper as one question, therefore we always include this. The following code example illustrate the common practice for SystemVerilog

```verilog
//a standard module
module modules(
  //declare input
  input A,
  //declare output
  output B
	);
  
	//intermediate wire
	wire C,D,E,F;
  //
  parameter datawidth;
  wire [datawidth-1:0] data;
  
  //assign is continuesly evaluate
  assign C = A&&B;       //AND
  assign D = C||A||B;    //OR
  assign E = A+B;        //numerical add NB the overflow bit
  assign F = A^B;		 //XOR
  
  wire [3:0] ab;
  
//end of line module
endmodule
```



