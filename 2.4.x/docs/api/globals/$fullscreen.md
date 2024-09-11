# <small>void</small> $fullscreen(<small>onEnterFullscreen: () => void?, onExitFullscreen: () => void?</small>)
Toggles fullscreen.
## Example
```javascript
$fullscreen(()=>{
    console.log("entered fullscreen!")
},()=>{
    console.log("exited fullscreen!")
})
```