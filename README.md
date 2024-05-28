# Chatroom Application

This is a simple chatroom application built in C++ using the concepts of socket programming and multi-threading. It supports real-time communication among multiple clients over a network.

## Features

- **Real-time Chatting**: Enables users to communicate with each other in real-time.
- **Multiple Clients**: Supports multiple clients simultaneously connecting to the server and chatting with each other.
- **Server-Client Architecture**: Utilizes a server-client architecture for handling client connections and managing communication.
- **Multi-Threading**: Uses multi-threading to handle multiple client connections efficiently.
- **Error Handling**: Implements error handling mechanisms to ensure stability and reliability of the chatroom application.

## How to run

1. Clone this repository
2. Run the following commands in your terminal :
```
g++ server.cpp -o server
g++ client.cpp -o client
```
3. To run the server application, use this command in the terminal :
```
./server
```

4. Now, open another terminal and use this command to run the client application :
```
./client
```

5. For opening multiple client applications, repeat step 4.

##Usage
- Upon running the client application, you will be prompted to enter your name.
- Once connected to the server, you can start chatting with other clients in the chatroom.
- Type your message in the terminal and press Enter to send it.
- To exit the chatroom, type #exit and press Enter.

##Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you find any bugs or want to improve the application.


