# Termix
A chatting client based on Socket.h in Linux terminal
___
## Terminal Commands
Step 1: `git clone https://github.com/codekhal/Termix.git` <br>
Step 2: `cd Termix` <br>
Step 3: `gcc server.c -lpthread` <br>
Step 4: `./a.out` <br>

**(ON Another TERMINAL)** <br> <br>
Step 1: `cd Termix` <br>
Step 2: `gcc client.c -lpthread` <br>
Step 3: `./a.out user1 hostIp 9999` <br>

**(ON Second Another TERMINAL)** <br> <br>
Step 1: `cd Termix` <br>
Step 2: `gcc client.c -lpthread` <br>
Step 3: `./a.out user2 hostIp 9999` <br>
___
## SCREENSHOT
![Screen](screen1.png)
