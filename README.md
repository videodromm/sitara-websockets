# sitara-websocketpp

A basic websocket library that can handle multiple connections to/from each Client or Server.  Architecture derived from the official documentations [utility](https://github.com/zaphoyd/websocketpp/tree/master/tutorials/utility_client)
[classes](https://github.com/zaphoyd/websocketpp/tree/master/tutorials/utility_server).

## Requirements
* websocketpp
* asio

All requirements are added as submodules to the project.  To download them, run:

```
git submodule update --init --recursive
```

## Usage
sitara-websockets uses property sheets to easily swap visual studio configuration settings to another project.  Adjust the macros in the property sheets to match your specific project's layout.

## Examples
* `exampleWebsocketServer` is a basic server that just prints any received messages to the console.
* `exampleWebsocketClient` is a basic client that periodically sends messages.
* `exampleWebsocketEchoServer` is a server that will print received messages to console and also echos the received message back to the sender.

## To Do
Currently, sitara-websockets does NOT support TLS/SSL.

## Contributing
This project uses the [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/) paradigm.  Before contributing, please make your own feature branch with your changes.

## More Information
* [Websocket++](https://www.zaphoyd.com/websocketpp/)
