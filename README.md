# Simple C++ Chat Application

This project is a basic multi-client chat application implemented in C++ using Winsock2 for networking. The application includes a server and multiple clients that can connect to the server to send and receive messages in real-time.

## Features

- **Multi-client support:** Multiple clients can connect to the server simultaneously.
- **Real-time messaging:** Messages sent by one client are broadcast to all other connected clients.
- **Client identification:** Each client is identified by a unique name, which is prepended to their messages.

## Components

### Server

- Listens for incoming client connections on a specified port.
- Handles multiple clients concurrently using threads.
- Broadcasts messages received from one client to all other connected clients.

### Client

- Connects to the server and allows the user to send and receive messages.
- Prompts the user for a unique chat name upon connection.
- Displays incoming messages from other clients in real-time.

