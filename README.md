# csc258-lab-3-splitters-adders-and-alus-solved
**TO GET THIS SOLUTION VISIT:** [CSC258 Lab 3-Splitters, Adders and ALUs Solved](https://www.ankitcodinghub.com/product/csc258-lab-3-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117502&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC258  Lab 3-Splitters, Adders and ALUs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
1 Learning Objectives

In this lab you will design (a) multiplexers that use the splitter component, (b) a simple ripple-carry adder, and (c) an Arithmetic Logic Unit (ALU), a fundamental component of each processor. You will also gain more practice with hierarchical design in Logisim and with using binary and hexadecimal numbers.

2 Marking Scheme

This lab is also worth 6% of your final grade, broken down as follows.

3 What You Need To Do

3.1 Preparation Before the Lab

As a refresher, carefully review the “Preparation Before the Lab” instructions in the Lab 2 handout.

You are required to complete Parts I to III of this lab by building and testing your circuit in Logisim. Make sure to complete all circuit diagrams and Logisim implementations outlined by the sections in Parts I to III marked as (PRELAB).

As part of this lab (and future labs), you must test your Lab 3 circuits in Logisim using reasonable test vectors written in the format described in the Lab 1 and Lab 2 handouts. The term test vector refers to one combination of inputs that you will use to test your design (similar to what you’d to check your circuit’s functionality anyway). Each simulation should consist of multiple test vectors, sufficient to demonstrate that your design functions as intended. Make sure to submit these test vector files as well.

You are also recommended to find information about Wiring in logisim reference.pdf. Wiring components will be useful for this lab.

3.2 In-lab Work

After you finish implementing and testing all of Parts I to III of the lab. You need to show your designs and demonstrate the operation of each part to the teaching assistants, including your test vectors.

3.3 Summary of Lab Requirements

The following is a summary of what you need to perform for this lab (and labs in general):

• Make sure to include the following in the pre-lab report:

– Answers to any question posed in the prelab sections

– Diagrams of your circuit designs (when asked)

– Any .circ files that you created to implement your designs

– Test vector files (when possible) or screenshots of your circuit’s performance given key inputoutput combinations (if test vectors aren’t possible)

• What to do in demo sessions:

– Review your pre-lab report (as necessary)

– Running and simulating your designs, using the Poke tool and/or test vectors

– Answer questions about your design and/or the handout

• Files required to upload:

– Pre-lab report (including circuit diagrams, answers to questions, etc)

– Logisim files (.circ)

– Test vectors (.txt)

4 Part I

For this part of the lab, you will learn how to use Splitter( ) to divide a multi-bit value into individual bits. These bits in turn will become the input signals to a 7-to-1 multiplexer that you create.

Generally, multi-bit values are used as a single unit to store integers or other data values. At other times though, these multi-bit values are just a grouping of related Boolean values. In this latter case, we often need to split up these bits and send them to different parts of the circuit. We accomplish this with the Splitter component. The Splitter can be found under Wiring in components. You can find more information about this component in Help &gt; User’s Guide &gt; Wiring bundles &gt; Splitters.

In addition to splitting multi-bit values into individual bits, splitters can also be used to concatenate individual bits into a single multi-bit value. You can adjust the multi-bit width, the ”fan out” number and the direction of the splitter in its properties.

For this part, the splitter will be used to provide inputs to a 7-to-1 multiplexer that you will create in Logisim. In the components list, find and select Plexers &gt; Multiplexer and then add one to the canvas. Clicking on the multiplexer you just created, go to Properties at the bottom left of the screen, change Select Bits to a value that allows 7 data inputs for your multiplexer.

(a) Assume that at the highest level, the multi-bit input is coming from the DE1-SOC switches, with the first data bit coming from SW[0]. The output of the multiplexer will be displayed on LEDR0. This is for labeling purposes only, not because we expect you to upload your design onto the DE1-SOC board.

(b) How big does the multi-bit input need to be to provide all the inputs to the 7-to-1 multiplexer? Provide your answer in your pre-lab report. (PRELAB)

2. Build your circuit in Logisim, using a 7-to-1 multiplexer and the splitter components. Make sure your implementation reflects your design in the previous step, including the labels. (PRELAB)

3. Simulate your circuit with test vectors in Simulate &gt; Test Vector…. Include a screenshot of the simulation output as part of your prelab report. (PRELAB)

5 Part II

a) Full adder circuit b) Full adder symbol

b a ci co

0 0 0

0 0 1 0 1 0

0 1 1 1 0 0

1 0 1

1 1 0 1 1 1 0

0

0

1

0 1

1

1

1 1

s b3 a3 c3 b2 a2 c2 b1 a1 c1 b0 a0 cin

0

1 1

0

0

0

c) Full adder truth table d) Four-bit ripple-carry adder circuit

Figure 1: A ripple-carry adder circuit.

Perform the following steps:

3. Simulate your 4-bit ripple-carry adder with test vectors for intelligently chosen values of A, B and cin. Include a screenshot of your test vector results in your prelab report. Note that as circuits get more complicated, it is not practical to simulate or test every single input case (in this case, 9 input bits would result in 29 test cases). This means that you must select an intelligently chosen subset of input values for your test vector. Here intelligently chosen means to find particular corner cases that exercise key aspects of the circuit. An example would be a pattern that shows that the carry signals are working, or how the circuit behaves with maximum and minimum values of A and B. Be prepared to explain why your test cases are good enough. (PRELAB)

6 Part III

Using Part II from this lab and the 7-segment decoder from Lab 2 Part III (import your earlier modules from File &gt; Merge and make sure all the modules have different names), you will implement a simple Arithmetic Logic Unit (ALU). The ALU generally has two data inputs and can perform multiple operations on these data inputs such as addition, subtraction, logical operations, etc. The operation performed by the ALU is determined by another multi-bit input (called the function input) that specifies the output operation for the ALU.

The easiest way to build this ALU is to:

1. Create a separate module for each of the required operations below and then connect the outputs of these modules to the inputs of a multiplexer.

2. Select the ALU operation to perform by connecting the select bits of the multiplexer to the inputs that provide the function value from the table below.

3. Display the unsigned inputs A and B on two seven-segments displays.

4. Display the output of the ALU on eight LEDs (binary value) as well as two seven-segment displays.

The following table shows the operations that you should implement in the ALU, given the specified function value.

function values ALU operation

0 Set the output to A+1, using the adder circuit from Part II of this Lab.

1 A + B using the adder from Part II of this lab

2 A + B using the Adder component found in Arithmetic

3 Bitwise A XOR B in the lower four bits and bitwise A OR B in the upper four bits

4 Output 1 (8’b00000001) if any of the 8 bits in either A or B are high, and 0 (8’b00000000)

if all the bits are low (also known as a reduction OR operation)

5 Make both inputs appear at the output, with A in the most significant (left-most) four bits and B in the least significant (right-most) bits.

A quick word on bitwise vs reduction operations:

• When performing logical operations (AND, OR, XOR, etc) on multi-bit input values, the reduction operation treats the input value as ”false” if the multi-bit value is 0 and ”true” otherwise. The output is a single true or false value, represented as a multibit 1 or 0,

• The bitwise operation treats each bit separately, where each bit in the output is the result of performing the bitwise operation on the corresponding bits in the input. So a bitwise OR would set the first digit in the output to the OR of the first digits in the two inputs, and so on for the remaining digits.

Note that the ALU takes in two unsigned 4-bit inputs A and B and outputs an unsigned 8-bit value called ALUout[7:0]. In some cases, the output will not require the full 8 bits so you will need to do something reasonable with the extra bits, such as making them 0 so that the value is still correct. Adding zeroes in front of any positive number is called sign-extension, and does not change the value of the number. In Logisim this is achieved by using Wiring &gt; Bit Extender (details can be found http://www.cburch.com/logisim/docs/2.6.0/en/libs/base/extender.html).

Perform the following steps to complete the lab:

2. Build the Logisim module for the ALU including all high-level inputs and outputs. (PRELAB)

3. Simulate your circuit with test vectors for a variety of input settings, ensuring the all the tests are passing. Include screenshots of your successful test output as part of your prelab. (PRELAB)

4. Prepare your design and implementation for your in-lab demo. (PRELAB)
