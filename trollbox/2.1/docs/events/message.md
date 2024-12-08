# <small>event</small> message
Fired when a user sends a message.
## Structure
### Inbound
An object with the following properties:
#### <small>string</small> msg
The message's content.
#### <small>string</small> home
The author's user id
#### <small>number</small> date
The timestamp of when the message was sent.
#### <small>string</small> nick
The nickname of the person who sent the message.
#### <small>string</small> color
The author's nickname color.
### Outbound
A string.

## Examples
### Outbound
```javascript
socket.emit("message","Hello, world!")
// Or, use the shorthand send function.
socket.send("Hello, world!")
```
### Inbound
```javascript
socket.on("message", (data) => {
    console.log(`${data.nick} said ${data.msg}`)
})
```