# 🌐 Network Fundamentals - Part 1

## 📌 What is a Network?

A computer network is a digital telecommunications network that allows devices (nodes) to communicate and share resources with one another.

### 💡 Examples of Shared Resources

* Files
* Printers
* Internet Connections
* Applications
* Storage Devices

---

## 📌 What is a Node?

A node is any device connected to a network that can send, receive, or forward data.

### 💡 Examples of Nodes

* Computers
* Laptops
* Smartphones
* Servers
* Printers
* Routers
* Switches

> Every device connected to a network is considered a node.

---

## 📌 What is a Client?

A client is a device or software application that requests and accesses services provided by a server.

### 💡 Examples

* A web browser requesting a webpage.
* A mobile app requesting data from a cloud server.

### 🎯 Cybersecurity Relevance

Many cyberattacks target client devices because they are often the entry point into a network.

---

## 📌 What is a Server?

A server is a device or software that provides functions, services, or resources to clients over a network.

### 💡 Examples

* Web Servers
* Database Servers
* File Servers
* Mail Servers

### Important Note

A device can act as both a client and a server depending on the situation.

---

# 🔀 What is a Switch?

A switch is a networking device that connects multiple devices within the same Local Area Network (LAN).

### ⚙️ How It Works

* Connects computers, servers, printers, and other devices.
* Usually contains multiple ports (24, 48, or more).
* Acts as a central connection point within a LAN.
* Allows devices to communicate and share data efficiently.

### Key Characteristics

* Operates within a single network.
* Forwards traffic only within the local network.
* Cannot directly connect your LAN to the Internet.

### 🎯 Cybersecurity Relevance

Understanding switches helps in:

* Network Enumeration
* VLAN Security
* MAC Address Table Attacks
* Traffic Analysis

---

# 🌍 What is a Router?

A router is a networking device designed to connect multiple separate networks together.

### ⚙️ How It Works

* Connects different networks.
* Routes data between networks.
* Commonly connects a LAN to the Internet.

### Key Characteristics

* Usually has fewer interfaces than switches.
* Provides connectivity between separate networks.
* Sends and receives traffic across the Internet.

### Example

```text
Laptop
   ↓
Switch
   ↓
Router
   ↓
Internet
```

### 🎯 Cybersecurity Relevance

Routers are critical for:

* Network Segmentation
* Traffic Filtering
* Firewall Rules
* Routing and Pivoting

---

# 🔥 What is a Firewall?

A firewall is a specialized network security device or software that monitors and controls incoming and outgoing network traffic based on predefined security rules.

### ⚙️ Functions

* Monitors network traffic.
* Allows or blocks connections based on configured rules.
* Protects networks and systems from unauthorized access.

### Features

* Can be placed inside or outside a network.
* Filters both incoming and outgoing traffic.
* Modern firewalls provide advanced filtering and inspection capabilities.

### Next-Generation Firewalls (NGFW)

Modern firewalls include:

* Deep Packet Inspection (DPI)
* Application Awareness
* Intrusion Prevention Features
* Advanced Threat Detection

---

# 🔥 Types of Firewalls

## 1️⃣ Network Firewall

Hardware-based security device that filters traffic between networks.

### Example

A firewall placed between a company's network and the Internet.

---

## 2️⃣ Host-Based Firewall

Software installed on an individual computer that filters incoming and outgoing traffic.

### Examples

* Windows Defender Firewall
* UFW (Linux)
* pf (FreeBSD)

### Purpose

Protects a single device from unauthorized access.

---

# 📝 Quick Revision

| Term     | Definition                                           |
| -------- | ---------------------------------------------------- |
| Network  | Collection of connected devices that share resources |
| Node     | Any device connected to a network                    |
| Client   | Requests services from a server                      |
| Server   | Provides services to clients                         |
| Switch   | Connects devices within a LAN                        |
| Router   | Connects different networks                          |
| Firewall | Controls and filters network traffic                 |

---
7. What is a firewall?
8. What is the difference between a network firewall and a host-based firewall?
