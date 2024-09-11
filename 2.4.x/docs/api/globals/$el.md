# <small>Object</small> $el(<small>selector?: HTMLElement, context?: HTMLElement</small>)
## Methods
### <small>void</small> create(<small>tag: string, childNode?: Node, appendTo?: Node</small>)
### <small>void</small> each(<small>selector: string, callback: (el: Element, index: number) => void</small>)
Loops over each element matching the selector.
## Returns
An object with the following methods:
### <small>Element</small> get()
### <small>Object | string</small> html(html: string)
### <small>Object</small> add(html: string)
### <small>Object</small> empty()
### <small>Object</small> each(selector: any, callback: (...args: any) => void)
### <small>Object</small> append(content: string | HTMLElement)
### <small>void</small> click()
### <small>void</small> trigger(eventType: string)
Dispatches an event with the `eventType` type.
### <small>any</small> on(eventTypes: string, selector: any, handler: any, useCapture?: boolean)
### <small>Object</small> off(eventTypes: string, selector: any, handler: any)
