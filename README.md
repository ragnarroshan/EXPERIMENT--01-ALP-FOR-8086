# EXPERIMENT--01-ALP-FOR-808

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
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
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  ALP 
```
MOV Ax,5782H
MOV Bx,23ABH
ADD Ax, Bx  
MOV [3001H],Ax
HLT
```
## Output  
<img width="1918" height="1015" alt="image" src="https://github.com/user-attachments/assets/45118de0-4b94-47fd-adbb-1416493d230b" />


## Subtraction   ALP 
```
MOV Ax,5782H
MOV Bx,23ABH
SUB Ax, Bx  
MOV [3003H],Ax
HLT
```
## Output  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/af72f927-8ebf-4c18-9fdb-cea6b898f128" />


## Multiplication alp 
```
MOV Ax,5782H
MOV Bx,23ABH
MUL Bx  
MOV [3005H],Ax   
MOV [3007h],Dx
HLT
```
 ## Output  
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/41103634-7747-442e-b8c0-f51faf8d5d06" />



## Division alp 
```
MOV Ax,5782H
MOV Bx,23ABH
DIV Bx  
MOV [3009H],Ax   
MOV [300BH],Dx
HLT
```
## Output  
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/0d75c857-3426-4ca0-926e-499cabdc7ce4" />


## And ALP
```assembly
MOV Ax,5782H
MOV Bx,23ABH
AND AX,Bx  
MOV [4001H],Ax   
HLT
```
## Output
<img width="1913" height="1018" alt="image" src="https://github.com/user-attachments/assets/14195b27-9ab1-4d30-bcd1-b8a52de32b2b" />



## OR ALP
```assembly
MOV Ax,5782H
MOV Bx,23ABH
OR AX,Bx  
MOV [4003H],Ax   
HLT
```
## Output
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/5173c8c3-811a-49ff-b059-0a7a6e4dfaa1" />



## NOT  ALP
```assembly
MOV Ax,5782H
NOT AX
MOV [4005H],Ax   
HLT
```
## Output
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/796ae530-88e4-415c-ab52-5c1dca9656a6" />



## XOR  ALP
```assembly
MOV Ax,5782H
MOV Bx,23ABH
XOR AX,Bx  
MOV [4007H],Ax   
HLT
```

## Output
<img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/cfe991a6-9f9a-4220-90a1-11fd9c72ccf1" />



## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








