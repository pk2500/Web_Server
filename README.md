# Web_Server
Web_Server_Assignment_2
In this lab, you will learn the basics of socket programming for TCP connections in Python: 1) how to create a socket, 2) bind it to a specific address and port, and 3) send and receive a HTTP packet. You will also learn some basics of HTTP header format.
You will develop a web server that handles one HTTP request at a time. Your web server should accept and parse the HTTP request, get the requested file from the server’s file system, create an HTTP response message consisting of the requested file preceded by header lines, and send the response directly to the client. If the requested file is not present in the server, the server should send an HTTP “404 Not Found” message back to the client.
