# Computer Networks & Systems Programming Portfolio

Welcome! This repository serves as a public directory and technical overview of the networking and systems programming projects I completed during my coursework at **California State University, Sacramento (Sac State)**. 

> ⚠️ **Note on Code Availability:** To uphold Sac State's Academic Integrity Policy and respect course copyrights, the actual source code for these repositories is kept strictly **private**. However, I am more than happy to do a live code walkthrough or share access with recruiters and hiring managers upon request.

---

## 🛠️ Projects Overview

### 1. Reliable UDP File Transfer (`ReliableUDP`)
*   **Language:** Java
*   **Core Concepts:** Transport Layer, UDP Socket Programming, ARQ Protocols, Congestion Control, Packet Loss Mitigation.
*   **Description:** Implemented a custom reliability layer on top of standard UDP to ensure guaranteed, error-free file transfer. Designed and integrated mechanisms mimicking TCP-like behavior, handling packet reordering, duplicate detection, timeouts, and retransmissions over a simulated lossy network.

### 2. Publish-Subscribe Server (`PubSubServer`)
*   **Language:** HTML / JavaScript / Java 
*   **Core Concepts:** Application Layer Architecture, Event-Driven Systems, Multi-threading, Pub/Sub Paradigm.
*   **Description:** Developed a highly scalable Publish-Subscribe server designed to decouple message producers (publishers) from consumers (subscribers). Built to route messages asynchronously based on specific topics, optimizing data flow and minimizing latency.

### 3. Linux Process Controller (`ProcessLifecycleLab`)
*   **Language:** C
*   **Core Concepts:** Operating Systems, Linux Kernel API, Process Forking, Inter-Process Communication (IPC).
*   **Description:** Built a lightweight system process controller for Linux environments. The application orchestrates a dynamic pool of child processes using native system calls (`fork`, `exec`). Programmed parental oversight to manage child lifecycles, handle worker exits, and recycle resources efficiently.

### 4. Verbose TCP Server (`TCPServer`)
*   **Language:** Java
*   **Core Concepts:** Network Architecture, TCP Handshake, Multi-threaded Socket Server, Remote Command Execution.
*   **Description:** Constructed a robust, verbose TCP server from scratch using standard socket APIs. Features comprehensive logging for active network states and connections. Designed a custom application-layer command protocol allowing clients to connect and securely trigger remote job commands on the host environment.

---

## 🚀 Key Technical Skills Demonstrated
*   **Networking Protocols:** TCP, UDP, IP, Custom Application Layer Protocols.
*   **Low-Level Systems:** POSIX Threads, Linux Process Lifecycle, Memory Management.
*   **Design Patterns:** Event-driven architecture, Producer-Consumer, Client-Server architecture.

## ✉️ Contact & Code Requests
If you are a technical interviewer, recruiter, or engineering manager interested in reviewing the underlying architecture or source implementations of these projects, please reach out to me:

*   **Email:** [rylandporter@gmail.com]
*   **LinkedIn:** [https://www.linkedin.com/in/ryland-porter-9444983a7]
