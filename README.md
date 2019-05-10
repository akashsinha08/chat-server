# chat-server
A simple Linux client server chat application using Socket programming C++
The client will connect to the server through an IP address specified. The server will listen for up to 5 requests at a time. Afterwards, the server will accept the request to connect from a client and messages will be sent back and forth through a buffer. Should either the client or server decide to stop, at the end we close the sockets and terminate the program.
Two files : 1 ) server.cpp 2 ) client.cpp
