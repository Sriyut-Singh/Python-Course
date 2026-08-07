# 📘 07 — Networking (Sockets)

**Author:** Sriyut Singh

A short side-quest into how Python programs talk to each other over a network, using the built-in `socket` module — the foundation of basic client-server communication.

## 📂 What's Inside

| Notebook | What it covers |
|---|---|
| `lec-01-socket-programming.ipynb` | Introductory notes on setting up a socket connection (opening a server and client file). |
| `lec-02-server.ipynb` | Building a basic TCP **server** — creating a socket with `socket.AF_INET`/`socket.SOCK_STREAM`, binding to a host/port, listening for connections, and accepting client connections. |
| `lec-03-client.ipynb` | Building a matching TCP **client** — connecting to the server, receiving data with `recv()`, and decoding the message. |

## 🧠 Key Concepts Practiced

- TCP sockets with Python's `socket` module
- Server: bind, listen, accept
- Client: connect, receive, decode
- Basic client-server communication pattern

## ▶️ How to Run

```bash
jupyter notebook
```
Run `lec-02-server.ipynb` first (it starts listening), then run `lec-03-client.ipynb` in a separate kernel/terminal to connect to it.

---
*Part of the [Python for AI/ML](../README.md) learning series by Sriyut Singh.*
