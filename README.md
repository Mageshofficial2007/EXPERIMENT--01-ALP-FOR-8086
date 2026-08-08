# EXPERIMENT--01-ALP-FOR-8086
## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 

7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
	 
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)


## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AX, 512AH
MOV BX, 7394H
ADD AX,BX
HLT
```
## Output  
<img width="1918" height="1141" alt="ADD" src="https://github.com/user-attachments/assets/951e2f60-16d5-48aa-b462-b53ca6ebbc81" />

## Subtraction   of 8 bit numbers  ALP 
```
MOV AX,512AH
MOV BX,7394H
SUB AX,BX
MOV [3003H],AX
HLT
```
## Output  
<img width="1915" height="1145" alt="SUB" src="https://github.com/user-attachments/assets/4b35765f-5d84-4a19-b7e2-38ef17bb37f6" />

## Multiplication alp 
```
MOV AX, 512AH
MOV BX, 7394H
MUL BX
MOV [3005H],AX 
MOV [3007H],DX
HLT
```
## Output  
<img width="1912" height="1147" alt="MUL" src="https://github.com/user-attachments/assets/1f1954cd-a256-48d8-ae65-c7b8714f214b" />

## Division alp 
```
MOV AX,512AH
MOV BX,7394H
DIV BX
HLT
```
## Output  
<img width="1143" height="1140" alt="DIV" src="https://github.com/user-attachments/assets/d9a9a79c-ad52-4b78-a575-639fb63650bb" />

## AND of 16-bit numbers ALP
```
MOV AX,05H
MOV BX,03H
AND AX,BX
MOV [4005H],AX
HLT
```
## output
<img width="1912" height="1146" alt="AND" src="https://github.com/user-attachments/assets/e8c4f6c7-fb64-44f2-91fb-320acd20c40a" />

## OR of 16-bit numbers ALP
```
MOV AX,512AH
MOV BX,7394H
OR AX,BX
MOV [3003H],AX  
HLT
```

## output
<img width="1918" height="1151" alt="OR" src="https://github.com/user-attachments/assets/d88761b6-b067-4670-b065-b2efc3a64cab" />

## NOT of 16-bit number ALP
```
MOV AX,512AH
MOV BX,7396H
NOT AX        
MOV [3003H],AX
HLT
```

## output
<img width="1157" height="1138" alt="NOT" src="https://github.com/user-attachments/assets/72f8a2d3-2674-4361-bf35-06fffd6f64d0" />

## XOR of 16-bit number ALP
```
MOV AX,512AH
MOV BX,7394H
XOR AX,BX
MOV [3000H],AX
HLT
```

## output
<img width="1152" height="1132" alt="XOR" src="https://github.com/user-attachments/assets/9740a542-3a80-45dc-a146-994e5ca2ff04" />

## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
