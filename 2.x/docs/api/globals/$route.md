# <small>void</small> $route(<small>newHash: string</small>)
Changes the URL hash without refreshing the page.
Also automatically adds a `!` to the start of `newHash` before applying.
## Example
```javascript
$route("myCustomHash") // the hash in the URL will be changed to #!myCustomHash
```