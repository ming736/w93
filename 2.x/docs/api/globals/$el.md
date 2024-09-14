# <small>Object</small> $el(<small>selector?: HTMLElement, context?: HTMLElement</small>)
## Methods
### <small>void</small> create(<small>tag: string, childNode?: Node, appendTo?: Node</small>)
### <small>void</small> each(<small>selector: string, callback: (el: Element, index: number) => void</small>)
Loops over each element matching the selector.
## Returns
An object with the following methods:
### <small>Element</small> get()
### <small>Object | string</small> html(<small>html: string</small>)
### <small>Object</small> add(<small>html: string</small>)
### <small>Object</small> empty()
### <small>Object</small> each(<small>selector: any, callback: (...args: any) => void</small>)
### <small>Object</small> append(<small>content: string | HTMLElement</small>)
### <small>void</small> click()
### <small>void</small> trigger(<small>eventType: string</small>)
Dispatches an event with the `eventType` type.
### <small>any</small> on(<small>eventTypes: string, selector: any, handler: any, useCapture?: boolean</small>)
### <small>Object</small> off(<small>eventTypes: string, selector: any, handler: any</small>)
