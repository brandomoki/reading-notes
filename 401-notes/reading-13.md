# Message Queues

## [Socket.io Chat Example](https://socket.io/get-started/chat/)

- Explain to a non-technical recruiter what the Chat Example (above) does.

  - 

- What proof of life are we getting on the backend from the above app?


- Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?


## [Rooms](https://socket.io/docs/v4/rooms)

- What is a room and how might a room be useful?

  - The chat room is built using socket.io and event are broadcasted to all that are listening this make it have an instant response and no need for making new request

- How do you join a room?

  - socket.join

- how do you leave a room?

  - socket.on("disconnect")

## [Namespaces](https://socket.io/docs/v4/namespaces/)

- What is a Namespace and what does it allow you to do?

  - This allows you to create a room 

- Each namespace potentially has its own what? (hint: 3 things)

  - event handlers
  - rooms
  - middlewares

- Discuss a possible use case for separate namespaces

  - To create private rooms

## [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
  