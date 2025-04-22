# EXPERIMENT 01 ALP FOR 8086
Name : SHUBHAVI M
Roll no: 212223040199
Date of experiment : 11.03.2025





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

## Addition  of 8 bit ALP 
```
org 100h
MOV AX,5123H
MOV BX,1142H
ADD AX,BX
ret
```
## Output  
![Screenshot 2025-03-12 190010](https://github.com/user-attachments/assets/7c5af691-69ff-458d-a05a-1c8c1ed51551)

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h
MOV AX,[5000h]
MOV BX,[5002h]
SUB AX,BX
ret
```
 
## Output 
![Screenshot 2025-03-12 205707](https://github.com/user-attachments/assets/6ad2dd84-e2cb-4af6-b4aa-d30ee2067f35)

## Multiplication of 8 bit numbers ALP
```
org 100h
MOV BX,1200h
MOV AX,BX
MOV CX,120h
MUL CX
ret
```

 ## Output  
 ![Screenshot 2025-03-12 205850](https://github.com/user-attachments/assets/66294e21-f663-458b-b934-d980928d62d5)

## Division of 8 bit numbers ALP
```
org 100h
MOV AX, 0009H   
MOV BL, 02H     
DIV BL    
ret
```

## Output  
![Screenshot 2025-03-12 210013](https://github.com/user-attachments/assets/6569f255-4d63-46ea-a766-5d3a0a72f6bd)


## And of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```

## Output
![Screenshot 2025-03-12 210139](https://github.com/user-attachments/assets/3e79606b-3f1a-4df0-aa26-f1ba297ffd84)


## OR of 8 bit numbers ALP
```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```

## Output
![Screenshot 2025-03-12 210256](https://github.com/user-attachments/assets/884e1290-2880-46a6-9656-a71508765f07)

## NOT of 8 bit number ALP
```
MOV AL,65H
NOT AL
HLT
```

## Output
![Screenshot 2025-03-12 210408](https://github.com/user-attachments/assets/f992a43a-6850-46da-aedb-28a36c33d467)

## XOR of 8 bit number ALP
```
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
![Screenshot 2025-03-12 210511](https://github.com/user-attachments/assets/1e44a56e-444d-4794-8b9c-c450cc9fe509)

## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








