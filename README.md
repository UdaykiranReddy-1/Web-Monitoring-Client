# Web-Monitoring-Client
This is a python project that works on **Socket Programming** on two different machines : one being server , and the other being client
In Client , you can the enter the address of a Website to check it's response status(Is it active , running successfully or facing any difficulty and responding with errors.)
The entered address is received to the server and it checks the status, then returns back that to client in order to display it to the user. 

*Steps to Run :*
1) Take two computers , open server file in one , client in another.
2) Find out the WirelessLAN IP address of computer in which you are running server file through commands like `ipconfig` in Windows , `ifconfig` in Linux ,`ipconfig getifaddr en0` in MAC (Commands may change or may not work depends on latest developments , Look up to your current method and find out the IP address).
3) Now fill out the server's IP address field in both the files with the one you found Out.
4) Sometimes , the port I used may be colliding with some other functionality of your computer , if you face any complications in this issue , try using a free availabe port.
5) After setting up , make sure both are connected to internet.
6) Now first Run Server file by typing `python server.py` , next Run client file by typing `python client.py` in respective computers in their respective directories.

