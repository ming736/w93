# WindowInstance

Represents a window created by `$window`.

## Properties

### <small>number</small> id
The ID of the window.
### <small>[WindowOptions](api/interfaces/WindowOptions.md)</small> cfg
The config options that were used in creating this window.
### <small>[WindowElements](api/interfaces/WindowElements.md)</small> el

## Methods

### <small>void</small> close()
Closes the window.
### <small>void</small> destroy()
Closes the window without an animation.
### <small>void</small> maximize()
Maximizes the window.
### <small>void</small> minimize()
Minimizes the window.
### <small>void</small> restore()
Restores the window.
### <small>void</small> changeSize(<small>size: { width: number, height: number }, callback?: () => void</small>)
Changes the size of the window.

#### Parameters

- <small>Object</small> **size**
  - <small>number</small> **width**: The new width of the window.
  - <small>number</small> **height**: The new height of the window.
- <small>() => void</small> **callback?**

#### Example

```javascript
WindowInstance.changeSize({ width: 800, height: 600 }, () => {
  console.log("do stuff here");
});
```
### <small>void</small> active()
Activates the window.
### <small>void</small> changeTitle(<small>newTitle: string</small>)
Changes the title of the window.
### <small>void</small> changeIcon(<small>newIcon: string</small>)
Changes the icon of the window.
### <small>void</small> changeFooter(<small>newFooter: string</small>)
Changes the footer of the window.
