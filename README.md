# UDP-Server-using-nodejs
This repository contains a simple UDP server implemented in Node.js using the dgram module. The server listens for messages from clients over a specified UDP port.

How It Works


The UDP server is created using Node.js and binds to a specific port.
It listens for incoming UDP messages, processes them, and can send responses.
You can interact with the server by sending messages via a client (e.g., ncat, Netcat).


Known Issue


Error: Ncat: An existing connection was forcibly closed by the remote host.

This issue occurs when attempting to connect using ncat or similar clients. I have not yet resolved this issue. If you encounter this or know how to fix it, feel free to update this README with the solution!
