# /price/btn

Returns the current approximate supply of BTN.

## Endpoint

**Method:** `GET`  
**Response Type:** `application/json`  
**Response Format:** Plain Text

## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/supply/btn
```

Expected Response:

```
317236
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/supply/btn
```

Expected Response:
```
StatusCode        : 200
StatusDescription : OK
Content           : 317238
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 5
                    ratelimit-remaining: 3
                    ratelimit-reset: 33
                    connection: close
                    Content-Length: 6
                    Content-Type: application/json; charset=utf-8
                    D...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 5], [ratelimit-remaining, 3],
                    [ratelimit-reset, 33]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 6
```