# <small>Object</small> $date(<small>input: DateResolvable</small>)

!> <strong>Removed</strong><br>
`$date` was removed in version 2.0.0.  It only existed in version 2.0.0 beta (2.0.0b).

Converts a `DateResolvable` (anything that can be resolved to a `Date`) to an object containing the difference from now and the human-readable date.
## Returns
An object containing the following properties:
### <small>string</small> diff
The difference in seconds between `input` and now.
### <small>string</small> human
The human-readable date.
### <small>Date</small> date
The `Date` object.


