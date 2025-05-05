# m-eec041-project-3-solved
**TO GET THIS SOLUTION VISIT:** [M.EEC041 Project 3 Solved](https://www.ankitcodinghub.com/product/m-eec041-project-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94403&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;M.EEC041 Project 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1 – Introduction

This project will build a microprocessor with native support for complex number arithmetic. The main functional characteristics of the processor are:

<ul>
<li>– &nbsp;16 write/read registers, 64 bits (32 high bits real part, 32 low bits imaginary part)</li>
<li>– &nbsp;9 read-only registers with fixed complex constants (real part = -1, 0, +1, imaginary
part = -1, 0 +1)
</li>
<li>– &nbsp;Arithmetic and logic unit (ALU) operating in complex or real mode, integer two’s
complement signed
</li>
<li>– &nbsp;Three address register to register ALU instructions ( regdest &lt;- regA op regB )</li>
<li>– &nbsp;Synchronous 64 bit data RAM, supporting address space up to 16k (configurable)</li>
<li>– &nbsp;Support for configuring custom instructions by expanding ALU operations
The whole circuit must be synchronous with the positive edge of the clock signal and the global reset must be synchronous and active high.

Figure 1 presents a simplified block diagram of the processor. The register bank implements a set of 16 read/write registers, each one holding a complex number represented by the real part in the high 32 bits and the imaginary part in the low 32 bits. A set of additional read-only registers provide 9 useful complex constants: 0+0j, 0+1j, 1+0j, 1+1j, 0-1j, -1+0j, -1-1j, 1-1j, -1+1j.

The register bank provides two operands to the ALU and receives one 64-bit result to be stored into one of the 16 read/write registers. The data input to the register bank can be the output result produced by the ALU, the data read from an external port or the data read from the data memory.

Additionally to the register bank the processor includes a synchronous dual port data RAM with 1024×64 bit (8 kByte). The access to the data RAM is done only with load/store instructions to/from registers. The read/write operations to the RAM are synchronous with the master clock allowing simultaneous write and read operations.

The ALU implements the basic arithmetic and logic operations on complex numbers and the conversion from rectangular to polar and polar to rectangular representation of complex numbers. In addition to the complex arithmetic performed on data represented by the real and imaginary components, the ALU also supports the multiplication and division operations performed independently for the high 32 bits and the low 32 bits of each data. Due to the diversity of the complexity of the operations implemented by the ALU, the number of clock cycles required for each operation is variable for different operations. The operation of the ALU is controlled by two handshake signals start and done. The complete specification of the ALU operation will be detailed soon.

TBD: instruction set, instruction encoding, performance specs.
</li>
</ul>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Figure 1 – Block diagram of CPUX

2 – Register bank

Implements a set of 16 write/read registers of 64 bits with one input port inA and two output ports outA and outB. The output data ports outA and outB are driven by two additional registers, to allow operation in pipeline. When a read operation is performed and the input reg_cnstA/B is set, the corresponding output port is loaded with a pre- defined complex constant selected by the output port register address seloutA/B. The set of complex constants read when reg_cnstA/B is set to 1 are 0+j0, 1+j0, 0+j1, 1+j1, -1+j0, 0-j1, -1-j1, -1+j1 and 1-j1. The assignment of each constant to the output port register address seloutA/B is implementation dependent and can be chosen to minimize the complexity of the circuit.

The write and read operations are synchronous with the clock. The writing data into a register is set by the following inputs:

inA: the data to write

regwen: register write enable must be set to 1

selwreg: specifies the address (0 to 15) of the destination register

endwreg: enable data write: specifies which data field is written to the register, according to the following encoding: 2’b00: writes both data; 2’b01: writes only the high 32 bits; 2’b10: writes only the low 32 bits; 2’b11: swaps the high 32 bits with the low 32 bits

Data is read from the register bank to two independent ports in parallel, outA and outB. These two ports are implemented by two registers that are loaded with the data specified by the read register control signals:

seloutA/seloutB: the register address to read into port A and B or the constant specifier if cnstA/cnstB is 1

enrregA/enrregB: read enable, set to 1 to enable loading output registers outA/outB cnstA/cnstB: set to zero to load output ports with data from registers, set to 1 to load the output ports with the predefined constants. If cnstA/cnstB is 1 the read register address specifies the constant to load into the output ports.

The interface of this module and the Verilog header of the RTL code is presented in figure 2.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
module reg_bank(

input clock, // Master clock, active in the posedge

input reset, // Master reset, synchronous and active high

//— Data input port —————————————————-

</div>
</div>
<div class="layoutArea">
<div class="column">
input

<pre>input
input
input
</pre>
</div>
<div class="column">
<pre>[63:0]
[ 3:0]
[ 1:0]
</pre>
</div>
<div class="column">
regwe, // // inA, // selwreg, // endreg, // // //

</div>
<div class="column">
Register write enable: set to 1 to write the register selected by selwreg with the data at port inA

Data input

Select register index [0 to 15] to write data from port inA Data enable: 00-write both data fields

10/01-write only data field selected by 1’b0

</div>
</div>
<div class="layoutArea">
<div class="column">
11: swap high word and low word //— Data output ports ————————————————–

</div>
</div>
<div class="layoutArea">
<div class="column">
output reg [63:0] outA, // Data output A, registered

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>output reg [63:0] outB,
input  [ 3:0] seloutA,
</pre>
</div>
<div class="column">
// Data output B, registered

// Select register index [0 to 15] to output port outA

// Select register index [0 to 15] to output port outB

// Define whether the output ports A and B are loaded with

// the contents of the register bank or a fixed constant

// Read enable to output register outA (loads output register) // Read enable to output register outB (loads output register)

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>  input
  input
  input
  input
  input
</pre>
);

</div>
<div class="column">
[ 3:0]

</div>
<div class="column">
<pre>seloutB,
cnstA,
cnstB,
enrregA,
enrregB
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2 – Interface signals of the register bank (module reg_bank.v)

</div>
</div>
<div class="layoutArea">
<div class="column">
3 – Arithmetic and logic unit for complex numbers (module ALUX)

Module ALUX implements a set of functional units for performing arithmetic and logic operations on complex numbers. The ALUX receives two 64-bit operands and produces one 64-bit result. The operands and the result are composed by two 32-bit fields (signed integer), referred to by RE (the high 32 bits) and IM (the low 32 bits). For complex arithmetic operations, RE and IM represent the real and imaginary parts a complex data and for real arithmetic operations, the RE and IM fields are treated as two independent integers.

The interface of the ALUX is presented in figure 3. Signals inA and inB are the two 64-bit operands and outAB is the 64-bit result. The execution of the arithmetic and logic operations by module ALUX is controlled by two handshake signals start and done and a 5- bit control word, opr, defining the operation to execute.

The ALUX operation starts when signal start is set to 1 and the result is ready at output outAB when signal done is asserted. Both handshake signals are set to 1 during a single clock cycle. After initiating an operation, the input start must be ignored until the operation is completed (done set to 1).

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
The operations implemented by module ALUX require a variable number of clock cycles, as illustrated in the timing diagram of figure 4.

The initial set of operations to be implemented are described in next table, including the indication of the maximum duration of each operation, in clock cycles:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
opr index

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Operation: outAB &lt;= …

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Max clocks

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
0

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
A+B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
A–B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
A*B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
A/B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
40

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
RE(A) * RE(B), IM(A) * IM(B)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
RE(A) / RE(B), IM(A) / IM(B)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
34

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
A == B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
{ MOD(A), ANG(A) }

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
38

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
10 { MOD(B), ANG(B) }

</div>
<div class="column">
Complex / real addition Complex / real subtraction Complex multiplication Complex division

Real multiplication

Real division

Equality compare

Conversion to polar coords, operand A

38 Conversion to polar coords, operand B

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3 – Interface of the complex ALU (module ALUX.v)

Figure 4 – ALUX timing diagram

</div>
</div>
</div>
