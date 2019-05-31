# Network

## HTTP/2

- negotiation mechanism to elect protocol
- decrease latency in page load speed
  - header data compression
  - HTTP/2 server push [@Wiki](https://to.ly/1z5Uj)
  - requests pipelining
  - requests multiplexing

## Stateless Protocol

- a communications protocol that treats each request as an independent transaction that is unrelated to any previous request so that the communication consists of independent pairs of request and response.
- e.g. IP (Internet Protocol), HTTP (Hypertext Transfer Protocol)
- GOOD: simple server-side design (no need to dynamically allocate storage to deal with conversations in progress: if a client dies in mid-transaction, no part of the server system needs to be responsible for cleaning up the present state of the server)
- BAD: it may be necessary to include additional information in every request, and this extra information will need to be interpreted by the server.
- [@Wiki](https://to.ly/1z5T3)

## Stateful Protocol

- a protocol which requires keeping of the internal state on the server

## WebSocket

- a protocol providing full-duplex communications channels over a single TCP connection
- [@Wiki](https://to.ly/1z5T7)

## TCP (Transmission Control Protocol)

- It resides at the transport layer. Web browsers use TCP when they connect to servers on the World Wide Web, and it is used to deliver email and transfer files from one location to another.
- [@Wiki](https://to.ly/1z5Ta)

## OSI (Open Systems Interconnection) Network Model

1. Physical layer
2. Data Link layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

    [@Wiki](https://to.ly/1z5Tf)
