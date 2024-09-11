# <small>void</small> $store(<small>key: string, defaultValue: any, onSaveCallback?: (value: any) => void, onReadyCallback?: (value: any) => void</small>)

?> For the global that handles `IndexedDB` (and the filesystem), see [$db](/api/globals/$db.md).

Handles storage related operations via `localStorage`.

## Methods

### <small>any</small> set(<small>key: string, value: any, skipAutoReady?: boolean</small>)
Sets a key to the specified value.
### <small>any</small> get(<small>key: string</small>)
Gets a stored key.
### <small>void</small> update(<small>key: string, updateFunction: (value: any) => any</small>)
Updates a key using the specified `updateFunction`.
### <small>any</small> getRaw(<small>key: string</small>)
### <small>void</small> del(<small>key: string</small>)
Deletes a key.
### <small>(value: any) => void | undefined</small> onReady(<small>key: string, newCallback?: (value: any) => void</small>)
Gets the onReady callback of `key`.Will set the onReady callback to `newCallback` if passed. Returns the callback, or `undefined` if it does not exist.
### <small>(value: any) => void | undefined</small> onSave(<small>key: string, newCallback?: (value: any) => void</small>)
Gets the onSave callback of `key`.Will set the onSave callback to `newCallback` if passed. Returns the callback, or `undefined` if it does not exist.
### <small>void</small> autoReady(<small>key: string, value: any</small>)
Calls the ready callback of `key` if it exists. `value` will be passed to the callback.
### <small>void</small> autoSave(<small>key: string, value: any</small>)
Calls the save callback of `key` if it exists. `value` will be passed to the callback.
### <small>void</small> clear()
Clears all entries in `localStorage`.
### <small>Array\<string></small> keys()
Returns a list of every key inside `localStorage`.
