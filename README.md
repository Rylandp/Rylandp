# Computer Networks & Systems Programming Portfolio

Welcome! This repository serves as a public directory and technical overview of my personal projects, and networking and systems programming projects I completed during my coursework at **California State University, Sacramento (Sac State)**.

---

## 🛠️ Overview of a few of the projects I've done

### 1. DNS Security Simulation (`DNS-Security-Simulation`)
*   **Language:** Python
*   **Core Concepts:** DNS Security, DNSSEC Principles, Public-Key Cryptography, Digital Signatures, Client-Server Architecture.
*   **Description:** Developed a Python-based client-server DNS application demonstrating the core security principles behind DNSSEC. Implemented cryptographic verification to ensure DNS responses originate from a trusted server and have not been tampered with. Features public/private key management, signed responses, transaction ID and nonce validation, expiration checks, and tampering demonstrations to verify that modified or untrusted DNS responses are rejected.

### 2. Reliable UDP File Transfer (`ReliableUDP`)
*   **Language:** Java
*   **Core Concepts:** Transport Layer, UDP Socket Programming, ARQ Protocols, Congestion Control, Packet Loss Mitigation.
*   **Description:** Implemented a custom reliability layer on top of standard UDP to ensure guaranteed, error-free file transfer. Designed and integrated mechanisms mimicking TCP-like behavior, handling packet reordering, duplicate detection, timeouts, and retransmissions over a simulated lossy network.

### 3. Publish-Subscribe Server (`PubSubServer`)
*   **Language:** HTML / JavaScript / Java
*   **Core Concepts:** Application Layer Architecture, Event-Driven Systems, Multi-threading, Pub/Sub Paradigm.
*   **Description:** Developed a highly scalable Publish-Subscribe server designed to decouple message producers (publishers) from consumers (subscribers). Built to route messages asynchronously based on specific topics, optimizing data flow and minimizing latency.

### 4. Linux Process Controller (`ProcessLifecycleLab`)
*   **Language:** C
*   **Core Concepts:** Operating Systems, Linux Kernel API, Process Forking, Inter-Process Communication (IPC).
*   **Description:** Built a lightweight system process controller for Linux environments. The application orchestrates a dynamic pool of child processes using native system calls (`fork`, `exec`). Programmed parental oversight to manage child lifecycles, handle worker exits, and recycle resources efficiently.

### 5. Verbose TCP Server (`TCPServer`)
*   **Language:** Java
*   **Core Concepts:** Network Architecture, TCP Handshake, Multi-threaded Socket Server, Remote Command Execution.
*   **Description:** Constructed a robust, verbose TCP server from scratch using standard socket APIs. Features comprehensive logging for active network states and connections. Designed a custom application-layer command protocol allowing clients to connect and securely trigger remote job commands on the host environment.

---

## 🚀 Key Technical Skills Demonstrated
*   **Networking Protocols:** TCP, UDP, IP, DNS, DNSSEC, Custom Application Layer Protocols.
*   **Cryptography & Security:** Public-Key Cryptography, Digital Signatures, Cryptographic Verification, Response Integrity.
*   **Low-Level Systems:** POSIX Threads, Linux Process Lifecycle, Memory Management.
*   **Design Patterns:** Event-driven architecture, Producer-Consumer, Client-Server architecture.

## ✉️ Contact & Code Requests
If you have any questions, please reach out to me:

*   **Email:** [rylandporter@gmail.com](mailto:rylandporter@gmail.com)
*   **LinkedIn:** [https://www.linkedin.com/in/ryland-porter-9444983a7](https://www.linkedin.com/in/ryland-porter-9444983a7)
