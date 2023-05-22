Instructions to follow on the client side application


let ws = new WebSocket("ws://localhost:8080");

ws.onmessage = message => console.log(`${message.data}`);


Establish another connection with the exact same configuration above

//for client 1


ws.send("Hello world");