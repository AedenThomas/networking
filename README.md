# Network Programming Workspace

This workspace contains various examples of network programming in C. Here's a brief overview of the main directories and files:

- **BasicClient**: Contains basic client-server communication code. See client.c and server.c.
- **BasicNetworkProgramming**: Contains code for a server that reverses a string sent by a client. See server.c.
- **CaseChangeServerClient**: Contains client-server communication code. See client.c and server.c.
- **network_programming**: Contains code for a server that performs arithmetic operations sent by a client. See server.c.
- **SquareNumberServerClient**: Contains client-server communication code. See client.c and server.c.
- **TimeRequestServerClient**: Contains code for a server that sends the current time to a client upon request. See server.c.

## Individual Files:

- **client_socket_communication.c**: Contains code for a client that sends a message to a server and receives a response. See client_socket_communication.c.
- **client_socket.c**: Contains client socket communication code. See client_socket.c.
- **client.c**: Contains client communication code. See client.c.
- **echo_server_multi_client.c**: Contains code for an echo server that can handle multiple clients. See echo_server_multi_client.c.
- **icmp_flood.c**: Contains code for an ICMP flood attack. See icmp_flood.c.
- **multi_client_server.c**: Contains code for a server that can handle multiple clients. See multi_client_server.c.
- **raw_socket.c**: Contains code for raw socket communication. See raw_socket.c.
- **server_socket_communication.c**: Contains server socket communication code. See server_socket_communication.c.

## Building and Running

Each .c file can be compiled using gcc and run from the command line. For example, to compile and run client.c, you would use:

```bash
gcc client.c -o client
./client
```

Please replace client.c and client with the appropriate file and output names for other files.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.