# Socket.io

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

- What is a Web Socket?

  - WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection

- Describe the Web Socket request/response handshake and what happens once the connection is established.

  - Web socket request is sent out to the server and the server will respond if the client has access with a handshake after that a link is sent from server to the client

- Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

  - request

## [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

- What does the event handler io.on() do?

  - Executes an event upon receiving proper command

- Describe some possible proof of life or proof that the code works as expected

  - the ability to log to the console when a user connect or disconnects

- What does socket.emit() do?

  - this method broadcast a signal to all that are listening

## [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)


- What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

  - socket.io is a library that can used
  - websockets are the original technology

- When would you use Socket.IO?

  - When you want to build something that need real time response

- When would you use WebSockets?

  - When building something with real time response on the frontend

## [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

- What are a couple of key takeaways from this video?

  - allows different devices to connect to each other based on a 7 layer system

## [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

- Translate the gist of this video to a non-technical friend

  - Its basically the agreement between server and client done in small segments each step being an agreement hence the handshake. step one syn, step 2 syn-ack, step 3 ack