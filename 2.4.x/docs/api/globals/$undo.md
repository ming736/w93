# <small>Object</small> $undo(initialHistory: Array<any>)

## Returns
An object with the following methods:

### <small>Array<any></small> get()
Returns a copy of the history array up to the current cursor position.

### <small>number</small> cursor()
Returns the current cursor position in the history.

### <small>Array\<any></small> history()
Returns the entire history array.

### <small>void</small> clear()
Clears the history and resets the cursor.

### <small>any</small> add(item: any)
Adds an item to the history at the current cursor position and increments the cursor. Returns the added item.

### <small>void</small> each(callback: (item: any) => void)
Executes the provided callback function for each item in the history up to the current cursor position.

### <small>any</small> redo(callback?: (result: any) => void)
Executes the redo operation for the item at the current cursor position, if available. If a `callback` function is provided, it is called with the result. Returns the result of the redo operation.

### <small>any</small> undo(callback?: (result: any) => void)
Executes the undo operation for the item at the current cursor position, if available. If a `callback` function is provided, it is called with the result. Returns the result of the undo operation.