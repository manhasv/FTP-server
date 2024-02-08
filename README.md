# cs3700---FTP-server
High-level approach: 
1. Connect to the given FTP channel and logging in with given credentials
2. Based on the commands, extract the needed information and execute the commands
3. If the commands need a data channel, open one and close it once the data is transferred
4. Sending Quit to the FTP server to signal end of code.

Challenges: I didnot get how data channel work at first so I had to read some documents and eventually it clicked and I have it working. 

Overview of testing: Mostly, I run the commands alternatively on my terminal and check for the output from the print statements that I have in my codebase. I also occasionally check in my code on Github and turn it in on Gradescope to confirm that I have correctly implemented the functions too.