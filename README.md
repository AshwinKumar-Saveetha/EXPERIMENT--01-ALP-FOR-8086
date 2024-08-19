# EXPERIMENT--01-ALP-FOR-8086
Name : Ashwin Kumar A

Reg No: 212223040021

Date of experiment : 19.08.2024

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color  
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
<br/>
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)


















<br/><br/>
## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h 
MOV AX,11H;
MOV BX,22H;
ADD AX,BX;
MOV [5000H],AX;
ret
```
## Output 

![image](https://github.com/user-attachments/assets/a67a48ad-202b-4c43-838c-0cfaa3d112f7)

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV AX,09H;
MOV BX,07H;
SUB AX,BX;
MOV [5010H],AX;
ret
```
## Output  
![image](https://github.com/user-attachments/assets/72fd7636-a0a6-46ba-90cb-1c68b0fa7d1c)

## Multiplication alp 
```
org 100h
MOV AX,13H;
MOV BX,2H;
MUL BX;
MOV [5020H],BX;
ret
```
## Output  
![image](https://github.com/user-attachments/assets/ec8f9e5f-df88-473a-a3cb-56d45290d548)

## Division alp 
```
org 100h
MOV AX,20H;
MOV BX,2H;
DIV BX;
MOV [5030H],AX;
ret
```
## Output 
![image](https://github.com/user-attachments/assets/a9cfa35b-07a4-47c8-981a-645b2553bef1)

## Programs For Logical Operators

## AND
```
org 100h
MOV AX,16H;
MOV BX,32H;
AND AX,BX;
MOV [6000H],AX;
ret
```
## Output
![image](https://github.com/user-attachments/assets/02b79dfb-56cf-416b-9516-76c23c494aa8)

## OR
```
org 100h
MOV BX,4114H;
MOV AX,5001H;
OR AX,BX;
MOV [6010H],AX;
ret
```
## Output
![image](https://github.com/user-attachments/assets/22a30761-245d-4fc5-9d46-7ffe00775619)

## NOT
```
org 100h
MOV AX,32H;
NOT AX;
MOV [6020H],AX;
ret
```
## Output
![image](https://github.com/user-attachments/assets/e04f6a31-a43e-4271-b115-35c38db4bc5f)

## XOR
```
org 100h
MOV AX,32H;
MOV BX,13H;
XOR AX,BX;
MOV [6030H],AX;
ret
```
## Output
![image](https://github.com/user-attachments/assets/65e0cbf1-515b-4465-99cc-2066e6e01f5b)


## Result :
 
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.








