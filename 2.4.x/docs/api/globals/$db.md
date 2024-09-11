# <small>void</small> $db(<small>defaultValue: any, key: string, callback: (err: any, value: any) => void?</small>)

?> For the global that handles `localStorage` (and desktop icons), see [$store](/api/globals/$store.md).

Handles storage operations via `IndexedDB`.
## Methods

### <small>void</small> set(<small>key: string, value: any, callback?: (err: any, savedValue: any) => void</small>)
Sets a key to the specified value.
### <small>void</small> get(<small>key: string, callback?: (err: any, value: any) => void</small>)
Gets a stored key.
### <small>void</small> update(<small>key: string, updateFunction: (value: any) => any, callback?: (err: any, savedValue: any) => void</small>)
Updates a key using the specified `updateFunction`.
### <small>void</small> getRaw(<small>key: string, callback?: (err: any, value: any) => void</small>)
### <small>void</small> del(<small>key: string, callback?: (err: any, value: undefined) => void</small>)
Deletes a key.
### <small>void</small> clear(<small>callback?: (err: any, value: undefined) => void</small>)
Clears all entries in the `IndexedDB` table.
### <small>void</small> keys(<small>callback?: (err: any, value: Array\<string>) => void</small>)
Returns a list of every key inside storage to `callback`.