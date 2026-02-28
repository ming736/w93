# <small>void</small> $archive(<small>path: string, name?: string</small>)
Copies all files that are a descendant of `path` into a zip file with an optional `name` (will default to the folder name if not specified) and will prompt the user to download it.
## Example
```javascript
$archive("/a/boot","mybootfiles") // will copy everything in /a/boot into a zip file and prompt the user to download it
```