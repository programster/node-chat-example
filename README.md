# node-chat-example
A simple node chat example based on [a post I read on codeproject.com](https://www.codeproject.com/Articles/871622/Writing-a-Chat-Server-using-Node-js-TypeScript-and)


## How To Run
Make sure you have installed [NodeJs](http://blog.programster.org/install-nodejs/).

Start the server process by going to the server folder and execute:
```
npm start
```

Go to the client folder and open the index.html file twice so that it appears twice in your browser. Now enter messages into one and you will see that they appear in both browsers.

**Important:** The sockets have been configured to use `localhost` so your server will need to be the same computer as the one you are opening the web client in. Otherwise you need to change the hostname.
