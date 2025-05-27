# ⚙️ Distributed Systems Portfolio

This portfolio showcases my work in distributed systems — including protocols, concurrency models, and scalable architecture patterns. Projects demonstrate fault tolerance, inter-process communication, message-passing, and service coordination.

---

## 🌐 Projects

### 🔁 Distributed Key-Value Store
- A simple but resilient distributed key-value store using consistent hashing and node replication.
- Includes fault recovery and client request forwarding.
- **Tech**: Go, gRPC, Raft (custom)

---

### 👥 Leader Election Simulator
- Simulation of leader election in a cluster using the Bully and Raft algorithms.
- Visualized with CLI output or simple web UI.
- **Tech**: Python, Flask or Go, WebSockets

---

### 📦 Message Queue System
- Custom-built publish/subscribe message broker with durable topics and delivery guarantees.
- Inspired by Kafka’s log structure.
- **Tech**: Node.js, Redis, Docker

---

## 🧰 Tech Stack Summary

- Go, Python, Node.js
- gRPC, HTTP, WebSockets
- Raft, Bully, Paxos (simulation)
- Docker & Docker Compose
- Message queues (Redis pub/sub)
- CLI + Web-based tools

---

## 📚 Additional Notes

Find implementation strategies, theoretical breakdowns, and architecture notes in my companion repo:  
📘 [notes-distributed-systems](https://github.com/thelightbringer/notes-distributed-systems)

---

## 📌 What’s Next?

Planned additions:
- Distributed file system simulation
- Chubby-like lock service
- P2P communication via WebRTC
