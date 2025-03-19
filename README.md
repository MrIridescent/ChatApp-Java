# Online Chat Application

A simple multi-client chat application using Java socket programming.

## 📋 Features

- Supports multiple clients connected to a central server.
- Real-time message broadcasting.
- Simple text-based user interface for communication.

## 🛠️ Prerequisites

- Java Development Kit (JDK) 8 or later.

## 📂 Project Structure

```
ChatApp/
├── ChatServer.java
├── ChatClient.java
└── README.md
```

## 🚀 How to Run the Application

1. **Compile the code:**

```bash
javac ChatServer.java ChatClient.java
```

2. **Start the Chat Server:**

```bash
java ChatServer
```

3. **Start the Chat Clients:** (Open multiple terminals)

```bash
java ChatClient
```

4. **Chat away!**

## 📜 How It Works

1. The `ChatServer` listens for client connections on port `12345`.
2. Each client sends and receives messages via `ChatClient`.
3. Messages are broadcasted to all connected clients.

## 📧 Example Output

```
Client 1: Hello, everyone!
Client 2: Hi there!
Client 3: Welcome to the chat!
```

## 📚 Additional Notes

- Ensure the server starts before any client.
- Customize the port by modifying the `PORT` constant.

## 📝 Author

- Developed by [David Oke (Mr Iridescent)]
