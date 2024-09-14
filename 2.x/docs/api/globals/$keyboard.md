# <small>Object</small> $keyboard(<small>selector: HTMLElement | string, onKeyUp?: (key: string, obj: [KeyPress](/api/interfaces/KeyPress.md)) => void, onKeyDown?: (key: string, obj: [KeyPress](/api/interfaces/KeyPress.md)) => void</small>)

!> <strong>Removed</strong><br>
`$keyboard` was removed in version 2.0.0. It only existed in version 2.0.0 beta (2.0.0b). Use [`$key`](/api/globals/$key.md) instead.

Handles keyboard-related events.
## Returns
An object containing the following methods: 
### <small>this</small> config(<small>cfg: Object</small>)
### <small>this</small> up(<small>newCallback: (key: string, obj:&nbsp;[KeyPress](/api/interfaces/KeyPress.md)) => void</small>)
Sets the `onKeyUp` callback to `newCallback`.
### <small>this</small> down(<small>newCallback: (key: string, obj:&nbsp;[KeyPress](/api/interfaces/KeyPress.md)) => void</small>)
Sets the `onKeyDown` callback to `newCallback`.
### <small>this</small> combo(<small>cfg: Object</small>)
### <small>void</small> destroy()
Deletes this instance and unregisters all callbacks created by this instance.
