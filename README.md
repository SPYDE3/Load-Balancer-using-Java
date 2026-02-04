# Multithreaded Web Server

A Java-based multithreaded web server implementation designed to handle multiple client requests concurrently, improving server responsiveness and throughput.

---

## About

This project implements a basic web server using Java threads to enable handling multiple HTTP client connections simultaneously. It demonstrates core networking concepts, socket programming, and concurrent request processing.

---

## Features

- Multithreaded request handling for simultaneous clients  
- Basic HTTP/1.1 protocol support  
- Serving static files such as HTML, CSS, and JavaScript  
- Graceful handling of client connections and disconnections  
- Simple logging of incoming requests and responses  

---

## Technologies Used

- Java Socket programming  
- Multithreading with Java Threads  
- Standard Java I/O for file handling  
- HTTP protocol basics  

---

## Getting Started

### Prerequisites

- Java JDK 8 or higher  

---

### Running the Project

1. Clone the repository:git clone https://github.com/SPYDE3/Load-Balancer-using-Java.git
2.                                 
3. Navigate to the project directory and compile:
4. Run the server:
5. Access the server via a web browser at http://localhost:8080 (or configured port).

Project Structure
  src/ - Java source files for server implementation
  bin/ - Compiled bytecode (generated after compile)
  resources/ - Static files served by the server (if any)
  
Usage
  The server listens on a specified port and creates a new thread for each incoming client connection. Requests are parsed, and appropriate responses are served back to the client. Useful for learning the           fundamentals of web servers and concurrency.

Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests with enhancements or bug fixes.

License
This project is licensed under the MIT License.

Contact
For questions or suggestions, please open an issue or contact the maintainer.
