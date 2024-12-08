# <small>object</small> $io
Contains utility functions.

!> TODO: Fully add docs
## Properties
### <small>object</small> arg
Has a method called `arr`. Not sure what it does.
### <small>object</small> arr
### <small>object</small> Array
### <small>object</small> ArrayBuffer
### <small>object</small> Blob
### <small>object</small> File
### <small>object</small> fn
### <small>object</small> obj
### <small>object</small> Object
### <small>object</small> reg
Has a method called `escape` which escapes the text provided, likely used to prevent XSS attacks.
### <small>object</small> str
### <small>object</small> String
### <small>object</small> xml
Has a method called `parse` which parses xml and returns an `XMLDocument`.
## Methods
### <small>unknown</small> clone(<small>arg: any</small>)
Returns a clone of `arg`.
### <small>void</small> each(<small>obj: object, callback: (value: any, index: any, obj: object) => boolean?, thisArg?: any</small>)
Iterates over `obj` and calls `callback` for every entry. If `callback` returns `false` at any point, the iteration is stopped.
### <small>void</small> enum(<small>arr: Array, e: (value: any, index: number, o: (r: any) => unknown) => void, t: (...a: unknown) => unknown</small>)
### <small>boolean</small> equal(<small>arg1: any, arg2: any</small>)
Returns whether or not `arg1` and `arg2` are equal.
### <small>unknown</small> find(<small>e: any, o: any, r: any, t: any, n: any</small>)
### <small>string</small> is(<small>arg: any</small>)
Returns the class name of `arg`.
### <small>boolean</small> isArguments(<small>arg: any</small>)
Returns whether or not `arg` is an [`Arguments`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments) object.
### <small>boolean</small> isArray(<small>arg: any</small>)
Identical to [`Array.isArray`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray).
### <small>boolean</small> isDocument(<small>arg: any</small>)
Returns whether or not `arg` is a [`Document`](https://developer.mozilla.org/en-US/docs/Web/API/Document).
### <small>boolean</small> isElement(<small>arg: any</small>)
Returns whether or not `arg` is an [`Element`](https://developer.mozilla.org/en-US/docs/Web/API/Element).
### <small>boolean</small> isError(<small>arg: any</small>)
Returns whether or not `arg` is an [`Error`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error).
### <small>boolean</small> isFunction(<small>arg: any</small>)
Returns whether or not `arg` is a [`Function`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function).
### <small>boolean</small> isInfinity(<small>arg: any</small>)
Returns whether or not `arg` is `Infinity`.
### <small>boolean</small> isJSON(<small>arg: any</small>)
?> To check if something is an object, use [`isObject`](#boolean-isobjectarg-any) instead.

Returns whether or not `arg` is a valid JSON string.
### <small>boolean</small> isNative(<small>arg: any</small>)
Returns whether or not `arg` is a native JavaScript function provided by the browser.
### <small>boolean</small> isNodeList(<small>arg: any</small>)
Returns whether or not `arg` is a [`NodeList`](https://developer.mozilla.org/en-US/docs/Web/API/NodeList).
### <small>boolean</small> isNumber(<small>arg: any</small>)
Returns whether or not `arg` is a finite number.
### <small>boolean</small> isObject(<small>arg: any</small>)
?> To check if something is a JSON string, use [`isJSON`](#boolean-isjsonarg-any) instead.

Returns whether or not `arg` is a valid object.
### <small>boolean</small> isPrototype(<small>arg: any</small>)
Returns whether or not `arg` is the prototype of a class.
### <small>boolean</small> isReallyNaN(<small>arg: any</small>)
Returns whether or not `arg` is NaN (not a number).
### <small>boolean</small> isRegExp(<small>arg: any</small>)
Returns whether or not `arg` is a [`RegExp`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp).
### <small>boolean</small> isString(<small>arg: any</small>)
Returns whether or not `arg` is a string.
### <small>boolean</small> isWindow(<small>arg: any</small>)
!> This function does **NOT** check if `arg` is a [`WindowInstance`](/api/interfaces/WindowInstance).

Returns whether or not `arg` is a [`Window`](https://developer.mozilla.org/en-US/docs/Web/API/Window).
### <small>unknown</small> map(<small>r: any, i: any, o: any, a: any, u: any, c: any</small>)
### <small>void</small> onerror(<small>msg: string</small>)
Prints `$io error :  {msg}` into the console.
### <small>object?</small> parse(<small>json: string</small>)
Converts a JSON string `json` into an object.
### <small>string</small> stringify(<small>arg: any, indent: number?</small>)
Converts `arg` into a JSON string. If `indent` is provided, then the JSON string will be indented by `indent` amount of spaces.
### <small>string</small> type(<small>arg: any</small>)
Identical to [`is`](#unknown-isarg-any).