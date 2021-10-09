# blokdots-socketio-client

Example client for our Socket.IO Server integration

### Installation

Download or clone this repository, then run `npm install` to install the Socket.IO dependencies.

### Run

Before you run the script, it makes sense to start blokdots, set up a project that uses 
the Socket.IO Server component and make sure you have a hardware board connected.

You can download a blokdots example project for the Grove Beginner Kit here:  
[blokdots Socket.IO example](https://blokdots.com/documentation/examples/SocketIOExample/SocketIO.blokdots)

When you're ready to go, run the client from the command line with:  
`node index.js`

You should then see output in the terminal similar to this …
```
Waiting for connection …
Connected to blokdots with socket 2s3y0IFZJryaPujNAAAB
Received blokdots: Hey! null
Sending message 'count' with value 1
Sending message 'count' with value 2
Sending message 'count' with value 3
```

### Contact

If you have any problems, you can create an issue in this repository or write to us at support@blokdots.com

We hope you'll have fun with this!
