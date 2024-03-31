## Rust Multithreaded Web Server

Project aimed to build a web server using rust and:
* Learn a bit about TCP and HTTP.
* Listen for TCP connections on a socket.
* Parse a small number of HTTP requests.
* Create a proper HTTP response.
* Improve the throughput of server with a thread pool

---
The two main protocols involved in web servers are *Hypertext transfer protocol* (HTTP) and *Transmission Control Protocol (TCP). They are both request-response protocols, where a client initiates requests and a server listens to the requests and provides a response to the client. 

**TCP** is the lower-level protocol that describes the details of how information gets from one server to another but doesn't specify what that information is. 

**HTTP**: builds on top of TCP by defining the contents of the request and response. 

Here we will work with the raw bytes of TCP and HTTP requests and responses.