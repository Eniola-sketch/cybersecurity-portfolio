# HTTP in Detail

## Objective

Learn how HTTP works, how browsers communicate with web servers, and why HTTPS is more secure.

---

## What is HTTP?

HTTP (HyperText Transfer Protocol) is the protocol used for communication between a web browser and a web server. When you visit a website, your browser sends an HTTP request to the server, and the server responds with the requested webpage or data.

---

## How HTTP Works

1. A user enters a website address into their browser.
2. The browser sends an HTTP request to the web server.
3. The server processes the request.
4. The server sends back an HTTP response containing the webpage or other requested data.
5. The browser displays the content to the user.

---

## HTTP Methods

| Method | Purpose |
|---------|---------|
| GET | Retrieve information from a server |
| POST | Send data to a server |
| PUT | Update existing data |
| DELETE | Remove data |

---

## HTTP Status Codes

| Code | Meaning |
|------|---------|
| 200 | OK – Request was successful |
| 301 | Moved Permanently |
| 404 | Page Not Found |
| 500 | Internal Server Error |

---

## HTTP vs HTTPS

| HTTP | HTTPS |
|------|-------|
| Data is not encrypted | Data is encrypted using TLS |
| Less secure | More secure |
| Can be intercepted | Helps protect data during transmission |

---

## What is TLS?

TLS (Transport Layer Security) is a security protocol that encrypts data sent between a browser and a web server. It protects sensitive information such as usernames, passwords and payment details from being read by attackers while in transit.

---

## Security Observation

During this module, I identified a webpage using:

http://tryhackme.com/

instead of HTTPS.

This is a security issue because HTTP does not encrypt communication. Websites that handle sensitive information should use HTTPS to protect users.

---

## What I Learned

- How browsers communicate with web servers.
- The difference between HTTP and HTTPS.
- Why HTTPS uses TLS.
- Common HTTP request methods.
- Common HTTP status codes.
- Why checking for HTTPS is an important security practice.

---


## Screenshot

<img width="928" height="600" alt="image" src="https://github.com/user-attachments/assets/6186acc6-e89c-4ec7-917d-f42bfe3eeffb" />


---

## Reflection

This module helped me understand one of the core technologies behind the web. Understanding HTTP and HTTPS is important for cybersecurity because many web attacks involve intercepting, analysing or manipulating web traffic.
