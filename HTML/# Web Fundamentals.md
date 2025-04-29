# Web Fundamentals

This document provides an overview of key web concepts, including HTTP, TCP/IP, the Request-Response model, DNS, and other foundational web principles.

---

## Table of Contents
1. [HTTP (Hypertext Transfer Protocol)](#http-hypertext-transfer-protocol)
2. [TCP/IP (Transmission Control Protocol/Internet Protocol)](#tcpip-transmission-control-protocolinternet-protocol)
3. [Request-Response Model](#request-response-model)
4. [DNS (Domain Name System)](#dns-domain-name-system)
5. [Web Fundamentals](#web-fundamentals)

---

## HTTP (Hypertext Transfer Protocol)

HTTP is the foundation of data communication on the web. It is a stateless protocol used to transfer hypertext documents.

### Key Features:
- **Stateless**: Each request is independent of previous ones.
- **Methods**:
  - `GET`: Retrieve data.
  - `POST`: Submit data to be processed.
  - `PUT`: Update existing data.
  - `DELETE`: Remove data.
- **Status Codes**:
  - `200`: OK (Request succeeded).
  - `404`: Not Found (Resource not found).
  - `500`: Internal Server Error.

| Method | Description               |
|--------|---------------------------|
| GET    | Retrieve data             |
| POST   | Submit data               |
| PUT    | Update existing data      |
| DELETE | Remove data               |

---

## TCP/IP (Transmission Control Protocol/Internet Protocol)

TCP/IP is the suite of communication protocols used to interconnect network devices on the internet.

### Key Layers:
1. **Application Layer**: Handles high-level protocols like HTTP, FTP, etc.
2. **Transport Layer**: Ensures reliable data transfer (e.g., TCP).
3. **Internet Layer**: Routes data packets (e.g., IP).
4. **Network Interface Layer**: Handles hardware-level communication.

### Characteristics:
- **Reliable Communication**: TCP ensures data is delivered in order.
- **Packet Switching**: Data is broken into packets for transmission.

---

## Request-Response Model

The Request-Response model is the backbone of web communication. It describes how clients and servers interact.

### Workflow:
1. **Client Sends Request**: A browser sends an HTTP request to a server.
2. **Server Processes Request**: The server processes the request and prepares a response.
3. **Server Sends Response**: The server sends back an HTTP response (e.g., HTML, JSON).

### Example:
- **Request**: `GET /index.html HTTP/1.1`
- **Response**: `200 OK`

---

## DNS (Domain Name System)

DNS translates human-readable domain names (e.g., `www.example.com`) into IP addresses (e.g., `192.168.1.1`).

### Key Components:
- **DNS Resolver**: Resolves domain names to IP addresses.
- **DNS Server**: Stores domain-to-IP mappings.
- **Records**:
  - `A`: Maps a domain to an IPv4 address.
  - `AAAA`: Maps a domain to an IPv6 address.
  - `CNAME`: Alias for another domain.

| Record Type | Description                  |
|-------------|------------------------------|
| A           | Maps domain to IPv4 address |
| AAAA        | Maps domain to IPv6 address |
| CNAME       | Alias for another domain    |

---

## Web Fundamentals

### Key Concepts:
- **HTML**: The structure of web pages.
- **CSS**: Styling for web pages.
- **JavaScript**: Adds interactivity to web pages.
- **Web Servers**: Serve content to clients (e.g., Apache, Nginx).
- **Browsers**: Render web content (e.g., Chrome, Firefox).

### How the Web Works:
1. User enters a URL in the browser.
2. Browser sends an HTTP request to the server.
3. Server processes the request and sends back a response.
4. Browser renders the response (e.g., HTML, CSS, JavaScript).

---