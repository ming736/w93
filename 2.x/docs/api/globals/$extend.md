# <small>Object</small> $extend(<small>...objects: Object</small>)
Merges all the objects provided into one. Objects passed later will overwrite previous properties if they existed in an earlier object.
## Example
```javascript
$extend(
    {"hello": "world"},
    {"foo": "bar"}
) // returns {"hello": "world", "foo": "bar"}
```

```javascript
$extend(
    {"hello": "world"},
    {"foo": "bar"},
    {"hello": "user"}
) // returns {"hello": "user", "foo": "bar"}
```