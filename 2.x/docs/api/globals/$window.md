# <small>[WindowInstance](/api/interfaces/WindowInstance.md)</small> $window(<small>options: [WindowOptions](/api/interfaces/WindowOptions.md)</small>)

Creates a window.

## Properties
### <small>[WindowInstance?](/api/interfaces/WindowInstance.md)</small> current
The current window that is focused by the user.
### <small>Array\<[WindowInstance?](/api/interfaces/WindowInstance.md)></small> instances
An array of every window made. If a value is null, that window has been closed.
## Methods
### <small>void</small> active(<small>id: number</small>)
Activates the window with the specified `id`.
### <small>void</small> close(<small>id: number</small>)
Closes the window with the specified `id`.
### <small>void</small> config(<small>cfg: { [key: string]: any }</small>)
Extends the default config for new windows.
#### Example
```javascript
$window.config({ constrain: true })
// All future windows will not be able to go outside the viewport unless explicitly set to false
```
### <small>void</small> destroy(<small>id: number</small>)
Destroys the window with the specified `id`.
### <small>void</small> form(<small>title: string, options:&nbsp;[FormOptions](api/interfaces/FormOptions), callback: (ok: boolean, data: { [key: string]: any }) => void</small>)
Creates a form.
#### Example
```javascript
$window.form(
    "Example form", 
    {
        schema: {
            string: {
                title: "Enter text here",
                type: "string"
            },
            number: {
                title: "Enter a number here",
                type: "number"
            },
            array: {
                title: "Add stuff to this array",
                type: "array"
            },
            object: {
                title: "I'm just a title.",
                type: "object"
            },
            stringWithPresetValues: {
                title: "Choose an option.",
                type: "string",
                enum: ["Option 1", "Option 2"]
            },
            stringWithPresetValuesAndTitles: {
                title: "Choose an option again.",
                type: "string",
                enum: [
                    ["I'm Option 1!", "Option 1"],
                    ["And I'm Option 2!", "Option 2"]
                ]
            }
        }
    }, 
    function(ok, data) {
        if (ok) {
            $alert({msg: `You clicked OK.\n\n${JSON.stringify(data, null, 2)}`})
        } else {
            $alert({msg: `You didn't click OK.`})
        }
    }
)
```
### <small>void</small> maximize(<small>id: number</small>)
Maximizes the window with the specified `id`.
### <small>void</small> restore(<small>id: number</small>)
!> This method might be broken.