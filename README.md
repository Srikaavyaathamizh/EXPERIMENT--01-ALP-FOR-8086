![image](https://github.com/user-attachments/assets/efb3853d-017a-4b9a-a633-d6d9026cc599)# EXPERIMENT--01-ALP-FOR-8086
Name :SRIKAAVYAA T
Roll no :212223230214
Date of experiment :12/3/2025





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







## Programs for arithmetic  operations:
```
ORG 100h
mov ax, 1089h
mov bx, 1233h
add ax,bx
mov [6000h],ax

mov ax,[1000h]
mov bx,[1002h]
sub ax,bx
mov [6001h],ax

mov bx, 2248h
mov ax,bx
mov cx,13h
mov dx,cx
mul dx
mov [6002h],ax

mov bx,1099h
mov ax,[bx]
mov cx,05h
div cx
mov [6003h],ax


RET
```
# Output:
![Screenshot 2025-03-12 160757](https://github.com/user-attachments/assets/0925a213-9648-4e4f-b1c5-e9797c1ad159)

# Program For Logical Operations:
```
org 100h
MOV AX,1765H;
MOV BX,3855H;
AND AX,BX;
MOV [8000H],AX;


MOV AX,2902H;
MOV BX,3348H;
OR AX,BX;
MOV [8002H],AX;



MOV AX,9012H;
NOT AX;
MOV [8004],AX;


MOV AX,044H;
MOV BX,08H;
XOR AX,BX;
MOV [8006H],AX;

ret

```
# Output:
![Screenshot 2025-03-12 162604](https://github.com/user-attachments/assets/5de83882-b7e2-4aa4-8222-b388946213a9)













