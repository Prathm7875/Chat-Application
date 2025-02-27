# Chat Application

A simple client-server chat application built with Python using the `socket` library. This application allows multiple clients to communicate with each other via a central server.

---

## Features

- Real-time messaging between multiple clients.
- Centralized server for managing connections and broadcasting messages.
- Command-line interface for simplicity and easy debugging.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries**: 
  - `socket` (for networking)
  - `threading` (for handling multiple clients concurrently)

---

## Usage Instructions
- Start the server before connecting clients.
- Once connected, clients can send messages by typing and pressing Enter.
- All connected clients will receive the messages broadcast by others.
