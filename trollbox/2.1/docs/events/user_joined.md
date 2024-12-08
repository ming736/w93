# <small>event</small> user joined
## Structure
### Inbound
### Outbound
A tuple: the nickname of the bot (or user), the color, an empty string, and another empty string.

If called more than once, it will simply change the nickname and/or color of the bot/user.
## Examples
### Outbound
```javascript
socket.emit("user joined", "ExampleBot", "white", "", "")
```