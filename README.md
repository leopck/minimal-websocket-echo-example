# minimal-websocket-echo-example

As the title states. This is a simple example for those that are new to websocket on Javascript on Web Browser.

It works on Android, iOS, Windows and Linux, Chrome, etc...

## Usage

1. Implement a websocket server and host this website. You can host a websocket server using node.js, python or whatever language you like.

2. Once you have hosted this websocket server and hosted this website on your server (both of them must be at the same server means both this website and websocket server are hosted on the same machine) then you can access this website. This website will automatically connect to websocket.

3. Once connected you can click the button and it'll send the letter 'e' over and display on console and on your webpage the reply.


Change this to change what your message whenever you click the button.
```
function onSend(){
        socket.send('e');
}
```
