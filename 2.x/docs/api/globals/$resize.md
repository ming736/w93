# <small>Object</small> $resize(<small>element: HTMLElement, options?: string | Array</small>)
Allows `element` to be resized.
`options` can be either an array containing a list of resize handles, a string containing a list of resize handles seperated by `, ` (yes, the space is intentional) or `"all"`, to enable all handles.
## Resize handles
`n, w, e, s, nw, ne, sw, se`
## Returns
An object with the following methods:
### <small>void</small> destroy()
Disables resizing for `element`.