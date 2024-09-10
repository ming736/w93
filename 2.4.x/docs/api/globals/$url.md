# <small>Object</small> $url
URL related utilities.
## Properties
### <small>Object\<string,string></small> query
## Methods
### <small>Object\<string,string></small> parseQuery(<small>e: string</small>)
### <small>string</small> getExtention(<small>e: string</small>)
!> Janken likely accidentally misspelled this function's name while creating it.

Returns the extension of a url or file path.
### <small>string</small> getDomain(<small>url: string</small>)
Returns the domain inside the url.
### <small>void</small> checkImage(<small>url: string, callback: (valid: boolean, imageUrl: string?, image: Image?) => void</small>)
Checks whether or not an image url is valid. `callback` will be fired determining whether or not it is valid.

### <small>void</small> _checkFavicon(<small>e: string, callback: (...args: any) => void</small>)
### <small>void</small> checkFavicon(<small>e: string, callback: (foundFavicon: boolean, response: any)</small>)