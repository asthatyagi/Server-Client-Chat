# Server-Client-Chat
Server Client chat application through multithreading

Steps to run:
Open two terminals in the working directory

Step 1:
 Terminal 1 : gcc mainserver.c -o server -lpthread
 Terminal 2 : gcc mainclient.c -o client -lpthread

Step 2:
 Terminal 1 : ./server
 Terminal 2 : ./client 127.0.0.1 
 
 Step 3 :
 Type message in both terminals to send message from client to server and vice-versa.
 
