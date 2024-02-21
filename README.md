# Network Programming

A repo to contain implementations of Network Programming.

## Topics Covered

- OSI-7 Layer

- Sockets API, Datalink layer Protocol, TCP (SOCK_STREAM) and UDP (SOCK_DGRAM) protocols
- NS3 Simul

### OSI-7 Layer

1. App
2. Presentation
3. Session
4. Transport
5. Network
6. Data Link
7. Physical

### Sockets

Server and client socket on port 55555

1. Initialise WSA (WSAStartup())
2. Create a socket()
3. bind() the socket
4. listen() using the socket
5. accept() connection from socket
6. recv() using the accepted socket copy and flush client response on stack (as well as send())
7. disconnect
