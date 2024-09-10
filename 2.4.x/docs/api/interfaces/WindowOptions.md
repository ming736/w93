# <small>interface</small> WindowOptions

## Properties

### <small>string</small> title
The title of the window.
### <small>string</small> html
The HTML of the window.
### <small>string?</small> icon
The URL or path to the icon.
### <small>string?</small> help
The help text or HTML to display when the help button is clicked.

?> The help button will only appear when this property has a value.
### <small>string?</small> url
If present, the html of the window will become an iframe that points to `url`.
### <small>Array\<Menu>?</small> menu
!> TODO: Add documentation for this.

The menu buttons shown below the title bar.

### <small>boolean?</small> header
Whether or not the title bar should be visible.
### <small>number?</small> borderTopWidth
### <small>number?</small> borderBottomWidth
### <small>number?</small> borderLeftWidth
### <small>number?</small> borderRightWidth
### <small>unknown</small> baseWidth
### <small>unknown</small> baseHeight
### <small>number?</small> minWidth
The minimum width of the window.
### <small>number?</small> minHeight
The minimum height of the window.
### <small>number?</small> top
The amount of pixels away from the top of the viewport where the window should be.
### <small>number?</small> left
The amount of pixels away from the left of the viewport where the window should be.
### <small>boolean?</small> center
Whether or not the window will appear in the center of the viewport.
### <small>boolean?</small> noOut
### <small>boolean?</small> constrain
Whether or not the window should stay inside the viewport.
### <small>boolean?</small> ajax
### <small>boolean?</small> autoMaximize
Whether or not the window will be maximized when created.
### <small>boolean?</small> contextmenuOnBody
Whether or not the context menu can appear when right-clicking inside the body of the window.
### <small>boolean?</small> resizable
Whether or not the window can be resized.
### <small>boolean?</small> minimizable
Whether or not the window can be minimized.
### <small>boolean?</small> maximizable
Whether or not the window can be maximized.
### <small>boolean?</small> closeable
Whether or not the window can be closed.
### <small>boolean?</small> draggable
Whether or not the window can be dragged around.
### <small>boolean?</small> dockable
Whether or not the window will appear in the dock.
### <small>boolean?</small> activable
!> It is recommended NOT to use this.

Whether or not the window can be selected.
### <small>Array\<unknown>?</small> headerBtn
### <small>Function?</small> onopen
The function that is called when the window is opened.
### <small>Function?</small> onready
The function that is called when the window is ready.
### <small>Function?</small> onclose
The function that is called when the window is closed.
### <small>Function?</small> onok
The function that is called when the `OK` button is clicked.
### <small>Function?</small> oncancel
The function that is called when the `Cancel` button is clicked.
### <small>Function?</small> onminimize
The function that is called when the window is minimized.
### <small>Function?</small> ondrag
The function that is called when the window is dragged around.
### <small>Function?</small> ondragstop
The function that is called when the window is no longer being dragged around.
### <small>Function?</small> onresize
The function that is called when the window is resized.
### <small>Function?</small> onactive
The function that is called when the window becomes active.
### <small>Function?</small> ondestroy
!> It is recommended to use [onclose](#function-onclose) instead.

The function that is called when the window is destroyed.
### <small>string?</small> animationIn
The animation to use when the window is opened.
### <small>string?</small> animationOut
The animation to use when the window is closed.
### <small>string?</small> baseClass
### <small>string?</small> bodyClass
### <small>string?</small> style
The CSS to use in the window.
### <small>string?</small> dest
#### Default
`document.body`
### <small>string?</small> dock
### <small>unknown</small> contextmenu