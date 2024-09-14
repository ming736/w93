# <small>Object</small> $dom

!> <strong>Removed</strong><br>
`$dom` was removed in version 2.0.0. It only existed in version 2.0.0 beta (2.0.0b). Use [`$selection`](/api/globals/$selection.md) instead.

Handles selections.

## Methods
### <small>string</small> getSelection()
Returns the currently selected text.
### <small>void</small> createSelection(element: HTMLElement, start: number, end: number)
Selects text in `element`.
### <small>void</small> createSelection(element: HTMLElement, callback: (this: HTMLElement) => void)
Redraws `element`.