# 🔌 Socket Programming in C

## 📖 Introduction
This project demonstrates a **basic TCP client-server communication model** using **sockets in C**.  
It includes a **server** that listens for client connections and a **client** that connects to the server and exchanges messages.

### 🌟 What is Socket Programming?
**Socket programming** is a method used in networking to allow different applications to communicate over a network.  
Using **sockets**, we can establish **client-server communication**, where:
- The **server** listens for incoming connections on a specific port.
- The **client** connects to the server and sends messages.
- The server processes the request and responds accordingly.

This project provides a **practical implementation of TCP socket communication**, helping in understanding:
- **Socket creation and connection** (`socket()`, `connect()`, `bind()`, `listen()`, `accept()`).
- **Data transmission** between client and server (`send()`, `recv()`).
- **Basic networking concepts** (IPv4, TCP, ports).

---

## 💡 Project Overview
This project consists of:
- A **server** that listens on **port 8080** and responds to client messages.
- A **client** that connects to the server and sends a message.
- A simple **TCP connection**, ensuring reliable communication between the client and server.

---

## 🛠️ Features & Implementations

### 🔹 **Server Features**
✔ Creates a **TCP socket** and binds it to **port 8080**.  
✔ Listens for incoming client connections.  
✔ Accepts client connections and receives messages.  
✔ Sends a response message back to the client.  

### 🔹 **Client Features**
✔ Establishes a **TCP connection** to the server.  
✔ Sends a **"Hello from client"** message to the server.  
✔ Receives a **response from the server**.  

---

## 📂 Files in This Repository
- 📄 `server.c` - **Server-side C code** that listens for client connections.  
- 📄 `client.c` - **Client-side C code** that connects to the server and exchanges messages.  

---

## 🚀 Getting Started  

### 🔧 **How to Compile and Run**
1️⃣ **Compile the server and client**  
```sh
gcc server.c -o server
gcc client.c -o client
