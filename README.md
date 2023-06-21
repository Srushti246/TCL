# TCL WORKSHOP
## Introduction
TCL (Tool Command Language) is a scripting language used for rapid prototyping, automation, and embedded systems. TCL has wide range of applications in various domains, including software development, network programming, and testing. It is often used to create command-line interfaces, automate repetitive tasks, and develop cross-platform applications.
### Tasks ###   
1. Create command (for example. vsdsynth) and pass .csv from UNIX shell to TCL script.
2. Convert all inputs to format[1](which is understood by YOSYS tool) and SDC format and pass to Synthesis tool YOSYS.
3. Convert format[1] and SDC to format[2] and pass to timing tool Opentimer.(Opentimer is tool used to create the data sheet and accepts data in particular fashion.
## LINK
1. [Day 1](#day1)
2. [Day 2](#day2)
3. [Day 3](#day3)
4. [Day 4](#day4)
5. [Day 5](#day5)



Day 1

Three scenarios
 - when .csv file is not provided
 - when .csv provided which does not exist
 - '-help' find out usage
![image1](https://github.com/Srushti246/TCL/blob/main/Images/D1%20img%201.jpeg?raw=true)


Day 2
 
Creating Variables
![image2](https://github.com/Srushti246/TCL/blob/main/Images/getting%20vaiables%20name.jpeg?raw=true)

No of rows and columns
![image3](https://github.com/Srushti246/TCL/blob/main/Images/no%20of%20rows%20and%20cloumns.jpeg?raw=true)

Display of error message when require file is not found
![image4](https://github.com/Srushti246/TCL/blob/main/Images/constatrints%20file%20not%20found.jpeg?raw=true)

Display when the all required all files exist
![image5](https://github.com/Srushti246/TCL/blob/main/Images/constarints%20file%20found.jpeg?raw=true)


Day 3

snippet of creaing SDC constarints
![image6](https://github.com/Srushti246/TCL/blob/main/Images/SDC%20constraints%20creation.jpeg?raw=true)

Snippet of the SDC file
![image7](https://github.com/Srushti246/TCL/blob/main/Images/output%20port%20checks.jpeg?raw=true)


Day 4
### YOSYS
YOSYS is an open-source synthesis tool that converts RTL (Register Transfer Level) designs written in hardware description languages like Verilog or VHDL into a gate-level representation. It enables hardware designers to perform synthesis, optimization, and formal verification of digital circuits.

Tool introduction
![image8](https://github.com/Srushti246/TCL/blob/main/Images/hierarcy%20check%20to%20YOSYS.jpeg?raw=true)


If any module is not found it displays error flag as 1

![image9](https://github.com/Srushti246/TCL/blob/main/Images/error%20flag%20D4.jpeg?raw=true)

If all modules are defined well then it shows error flag as 0
![image10](https://github.com/Srushti246/TCL/blob/main/Images/hierarchy%20pass.jpeg?raw=true)

Hierarchy Check Pass
![image11](https://github.com/Srushti246/TCL/blob/main/Images/h%20check%20pass.jpeg?raw=true)

Hieratchy Fail snippet
![image12](https://github.com/Srushti246/TCL/blob/main/Images/hierarrchy%20check%20fail.jpeg?raw=true)

Day 5

Synthesis running successfully
![image](https://github.com/Srushti246/TCL/blob/main/Images/synthesis%20pass.jpeg?raw=true)

Synthesis error
![image](https://github.com/Srushti246/TCL/blob/main/Images/syntheisis%20fail.jpeg?raw=true)

![image](https://github.com/Srushti246/TCL/blob/main/Images/D5%20Mul_use.jpeg?raw=true)


