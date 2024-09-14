# <small>Object</small> $cli(<small>element: HTMLElement, options?: Object</small>)
Creates a command-line interface similar to that of the `terminal` app where `element` is the body of the cli.
## Methods
### <small>void</small> clearhistory()
Clears your history.
## Returns
An object with the following properties:

### <small>Object</small> cfg
### <small>boolean</small> cli
### <small>HTMLTextAreaElement</small> input
### <small>HTMLSpanElement</small> prompt

### <small>() => void</small> ondestroy
### <small>(inputValue: any) => boolean</small> onenter
### <small>(key: any, inputValue: any) => boolean</small> onkey

and the following methods:
### <small>void</small> destroy()
### <small>HTMLDivElement</small> log(<small>message: string, t: any, o: any</small>)
Identical to [`$log`](/api/globals/$log.md).
### <small>void</small> setFocus()