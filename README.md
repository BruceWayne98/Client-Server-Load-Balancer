#Client-Server-Load-Balancer
This is a set of programs that demonstrates how a server can divide and assign work to multiple clients in a distributed environment.

Requirements: Python 3.6, Windows

To run this program,

Download this project folder into a location on your computer
Extract this folder.
Open 2 powershell windows here
In the first one, let's say for the server, enter a command similar to this python .\launch_server.py 20 5678
In the second one, for creating clients, enter a command similar to this .\launch_clients.ps1 10 5678
20 indicates the number of tasks the server's pool should contain, 5678 indicates the port number on which to start the server

10 indicates the number of clients to create, 5678 indicates the port to connect to.
