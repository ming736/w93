# <small>Object</small> $socket(<small>url: string</small>)
A `WebSocket` wrapper.

## Returns
An object with the following properties:
### <small>WebSocket</small> conn
The current `WebSocket` instance.

<strong>and the following methods:</strong>

### <small>void</small> connect()
Connects to the server.
### <small>void</small> disconnect()
Disconnects the server.
### <small>this</small> on(<small>eventName: string, handler: (...args: any) => void</small>)
### <small>this</small> send(<small>eventName: string, message: string</small>)

?> You can leave `eventName` as `null`.

Sends a message to the server.