# <small>void</small> $notif(<small>options: string | Object, element?: string | HTMLElement</small>)
Creates a notification. If `options` is a string, that will be the body of the notification, otherwise the config options. If `element` is a string, that will be the title of the notification, otherwise unknown.
## Parameters
### options
Either a string or an object with the following properties:
#### <small>string?</small> title
The title of the notification.
#### <small>string</small> text
The text to show in the notification.
#### <small>string?</small> description
#### <small>string?</small> body
#### <small>Element?</small> default
#### <small>HTMLElement?</small> dest
The element to append the notification to.
#### <small>boolean?</small> delay
#### <small>number?</small> speed
How long until the notification disappears.