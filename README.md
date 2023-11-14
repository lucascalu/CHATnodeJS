# Socket.IO chat example

This is the source code for a very simple chat example used for the [Tutorial](https://socket.io/docs/v4/tutorial/introduction) guide of the Socket.IO website.

You can run this example directly in your browser on:


<p>Ao iniciar usar o comando npm install</p>

- [CodeSandbox](https://codesandbox.io/p/sandbox/github/socketio/chat-example?file=index.js)
- [StackBlitz](https://stackblitz.com/github/socketio/chat-example?file=index.js)
- [Repl.it](https://repl.it/github/socketio/chat-example)

  <p>

    CREATE TABLE IF NOT EXISTS messages (
  id INT AUTO_INCREMENT PRIMARY KEY,
  client_offset VARCHAR(255) UNIQUE,
  content TEXT
);

  </p>
