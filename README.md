# CS371-PA1
PA1: Socket Programming and Epoll

## Compiling the project
`gcc -o pa1_skeleton pa1_skeleton.c -pthread`

## Example Run
Start the server first with designated IP and port number

`./pa1_skeleton server 127.0.0.1 12345`

Then run the client with 4 threads, each thread sends 1000000 messages.

The client threads will connect with designated server IP and port number

`./pa1_skeleton client 127.0.0.1 12345 4 1000000`