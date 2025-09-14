# Networking basics #0

## 📖 Project Overview
This project introduces the fundamentals of computer networking using the **OSI model** as a conceptual framework.  
It focuses on understanding how devices communicate across local and global networks, the protocols that support data exchange, and the basic diagnostic tools available in Unix-like environments.

The work is divided into multiple tasks, each covering an essential concept and culminating in a practical Bash script or a multiple-choice answer.

---

## 🎯 Learning Objectives
By the end of this project, you should be able to:
- Explain what the **OSI model** is and describe its layered architecture.
- Differentiate between **LAN, WAN, and the Internet**.
- Understand the purpose of **MAC and IP addresses** and their differences.
- Compare **UDP** and **TCP** protocols and know when each is used.
- Recognize the role of **ports** and how to list listening network services on a machine.
- Use **ICMP (ping)** to check if a host is online and measure response times.

---

## 📝 Tasks

### Task 0. OSI model
- Multiple choice questions on the OSI model.
- Understand that the OSI model is a conceptual framework, not a tangible implementation.
- Learn the hierarchical organization of its 7 layers.

---

### Task 1. Types of network
- Multiple choice questions about **LAN**, **WAN**, and the **Internet**.
- Identify which type of network is used in different real-life scenarios (local PC, offices in different buildings, accessing Google on mobile).

---

### Task 2. MAC and IP address
- Multiple choice questions on the difference between **MAC addresses** and **IP addresses**.
- MAC = physical unique identifier of a network interface.  
- IP = logical address similar to a postal address.

---

### Task 3. UDP and TCP
- Multiple choice questions distinguishing **TCP** and **UDP**.  
- TCP: reliable, ordered, slower but ensures delivery.  
- UDP: fast, lightweight, may lose packets.  
- Understand through analogy (TCP worker confirming deliveries vs UDP sending quickly without checks).

---

### Task 4. TCP and UDP ports
- Write a Bash script to list **listening ports**.  
- Show **PID** and **program name** associated with each socket.  
- Include both **Internet connections (TCP/UDP)** and **UNIX domain sockets**.  
- Learn well-known ports: `22 (SSH)`, `80 (HTTP)`, `443 (HTTPS)`.

---

### Task 5. Is the host on the network
- Write a Bash script to ping an IP address given as argument.  
- If no argument is passed, display a usage message.  
- Send **5 ICMP packets** to the target host.  
- Learn how `ping` works with ICMP to check availability and measure latency.

---

## 🛠️ Requirements
- Allowed editors: `vi`, `vim`, `emacs`
- All Bash scripts will be interpreted on **Ubuntu 22.04**
- All files must end with a new line
- A `README.md` file is mandatory
- All Bash scripts must be executable
- Scripts must pass **shellcheck** without errors
- First line of scripts: `#!/usr/bin/env bash`
- Second line of scripts: comment explaining the script’s purpose

---

## ✅ Conclusion
This project provides a hands-on introduction to the essential concepts of networking.  
From abstract models like OSI, to practical commands like `ping` and `ss/netstat`, you gain both **theoretical understanding** and **practical skills** for diagnosing and working with networks in a Unix environment.