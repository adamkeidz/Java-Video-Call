# Java Video Call

Java Video Call is a video calling application written in Java. It uses JavaFX for the graphical user interface, JavaCV for video processing, and Java-WebSocket for networking.

## Features
- Video calling between multiple clients connected to a server
- Video capture from the webcam
- Display of video frames on the user interface

## Getting Started

### Prerequisites

This application requires the following to be installed on your machine:
- Java
- JavaFX
- JavaCV
- Java-WebSocket

### Running the Server

1. Run the `VideoCallServer` main method to start the server.
2. The server will start listening for incoming client connections.

### Running the Client

1. Run the `VideoCallClient` main method to start a client.
2. The client connects to the server and starts sending and receiving video frames.

## How it Works

The application works by establishing a WebSocket connection between the client and the server. The client captures video frames from the webcam using JavaCV and sends these frames to the server. The server then broadcasts these frames to all connected clients. The clients receive these frames and display them on the user interface using JavaFX.
