# iot_assignment

A simple tcp client server application that describes the communication between the client and a server. 
This is a simple TCP server which handle multiple clients.

How to run:

Server on linux:
gcc server.c -o server -lpthread

./server


Client:
gcc client.c -o client -lpthread

./client

Get Parameters from server:
write commands in quotation "":

"G"     Gps data
"D"     Get date
"A"     Get Temperature
  

