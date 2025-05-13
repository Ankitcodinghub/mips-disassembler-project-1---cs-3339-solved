# mips-disassembler-project-1---cs-3339-solved
**TO GET THIS SOLUTION VISIT:** [MIPS Disassembler Project 1 – CS 3339  Solved](https://www.ankitcodinghub.com/product/mips-disassembler-project-1-cs-3339-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;50004&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MIPS Disassembler  Project 1 – CS 3339&nbsp; Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>PROBLEM STATEMENT</h1>
&nbsp;

In this project, you will write a disassembler that reads MIPS machine instructions from a (simplified) binary executable file and prints each assembly language instruction to the screen.

&nbsp;

Write your disassembler code in the provided C++ code skeleton, disassembler.cpp.&nbsp; All of your code will go in the disassembleInstr function.&nbsp; You should read and understand the rest of the code, as it will form the basis for the remaining projects.&nbsp; Your disassembler only needs to support the MIPS instructions listed in comments in the code skeleton.

&nbsp;

Your disassembler must precisely match the output in the sample output files, including all whitespace and formatting.&nbsp; Note that all constants are in decimal representation except PC values and jump and branch targets, which are in hexadecimal.

&nbsp;

Please use the updated “green card” provided in class and posted on TRACS.&nbsp; Note that the green card says the sll instruction means ‘rd = rt &lt;&lt; shamt’ whereas the official MIPS standard says it means ‘rd = rs &lt;&lt; shamt’.&nbsp; We will follow the provided MIPS standard for all shift instructions.&nbsp;&nbsp; Make your code match the comments and output files.

&nbsp;

<strong>&nbsp;</strong>

<h1>ASSIGNMENT SPECIFICS</h1>
&nbsp;

This project is to be submitted individually, and you should be able to explain all code that you submit.&nbsp; You are encouraged to discuss, plan, design, and debug with fellow students.

&nbsp;

All provided files are on TRACS.&nbsp;&nbsp; After moving the compressed tar file to your home space on zeus, the following command will extract the files:

&nbsp;

$ tar xzvf cs3339_project1.tgz

&nbsp;

This will create a directory called project1 that contains several sample executables (*.mips) for testing your disassembler, the corresponding expected output files (*.dis), the disassembler code skeleton (disassembler.cpp) to which all your code must be added.

&nbsp;

Once you have added the missing code to the .cpp file, compile the file with this command:

&nbsp;

$ g++ -O3 disassembler.cpp -o disassembler -std=c++11

&nbsp;

&nbsp;

1

Assuming the compilation succeeded, you can run your disassembler on the provided *.mips files.&nbsp; For example, to disassemble test1.mips, run this command:

&nbsp;

$ ./disassembler test1.mips

&nbsp;

To output the disassembly to a file instead of to the screen and then compare the output to the provided expected output, run these 2 commands:

&nbsp;

$ ./disassembler test1.mips &gt; test1.out

$ diff –w test1.out test1.dis

&nbsp;

If the diff command produces any output to the screen, then the two files are <em><u>not</u></em> identical and you need to change your disassembler code so that the outputs match.

&nbsp;

Additional Requirements:

&nbsp;

<ul>
<li><strong>Your code must compile with </strong><strong>g++ and run on zeus.cs.txstate.edu </strong></li>
<li>Do not change any code outside of the disassembleInstr function and name block</li>
<li>Your code must be well-commented, sufficiently to prove you understand its operation</li>
<li>Make sure your code doesn’t produce unwanted output such as debugging messages</li>
<li>Make sure your code is correctly indented and uses a consistent coding style</li>
<li>Do not use TAB characters for indentation! (Use a consistent # of spaces per indent level)</li>
<li>Clean up your code before submitting: i.e., make sure there are no unused variables, unreachable code, etc.</li>
</ul>
&nbsp;
