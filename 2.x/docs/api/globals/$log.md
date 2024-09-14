# <small>HTMLDivElement</small> $log(<small>message: string, t: any, o: any</small>)
Logs `message` to the newest terminal.
## Methods
### <small>HTMLDivElement</small> clear(<small>message: string, t: any, o: any</small>)
Clears all text inside the terminal.
### <small>HTMLDivElement</small> error(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a red color.
### <small>HTMLDivElement</small> succes(<small>message: string, t: any, o: any</small>)

!> Janken accidentally misspelled this function's name as `succes` instead of `success`.

Logs `message` to the terminal with a dark green color.

### <small>HTMLDivElement</small> fail(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with red text prefixed by `✘`.
### <small>HTMLDivElement</small> pass(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with dark green text prefixed by `✔`.
### <small>HTMLDivElement</small> warn(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal.
### <small>HTMLDivElement</small> info(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with blue text prefixed by `ℹ`.
### <small>HTMLDivElement</small> bold(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a bold font weight.
### <small>HTMLDivElement</small> italic(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with an italic font style.
### <small>HTMLDivElement</small> red(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a red color.
### <small>HTMLDivElement</small> blue(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a blue color.
### <small>HTMLDivElement</small> green(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a green color.
### <small>HTMLDivElement</small> white(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a white color.
### <small>HTMLDivElement</small> yellow(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a yellow color.
### <small>HTMLDivElement</small> cyan(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a cyan color.
### <small>HTMLDivElement</small> magenta(<small>message: string, t: any, o: any</small>)
Logs `message` to the terminal with a magenta color.
### <small>HTMLDivElement</small> html(<small>message: string, t: any, o: any</small>)
Logs `message` to the console as HTML.
### <small>HTMLDivElement</small> autolink(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> code(<small>message: string, t: any, o: any</small>)
Logs `message` to the console in a codeblock.
### <small>HTMLDivElement</small> pad(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> right(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> center(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> repeat(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> stack(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> save(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> stay(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> id(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> fast(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> group(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> noop(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> obj(<small>message: string, t: any, o: any</small>)
### <small>HTMLDivElement</small> end(<small>message: string, t: any, o: any</small>)
## Chaining
`$log` methods can be chained like this:
```javascript
$log.red.bold("red and bold text!")
```