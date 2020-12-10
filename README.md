# roundtrip-node
A round trip server for the web socket protocol

If you have no websocket client at hand, you can install `wscat`

```
npm install -g wscat
```

When the server is running on localhost, you can test the server from the
CLI using the below command, type in some text and hit return.

```
wscat -c wss://localhost:8080
```
