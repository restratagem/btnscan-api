# /price/btn

Returns the total amount of transactions processed by the network to date.

## Endpoint

**Method:** `GET`  
**Response Type:** `application/json`  
**Response Format:** Plain Text  

Syntax:

```
https://btn.api.restratagem.com/tx/total
```

## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/tx/total
```

Expected Response:

```json
81080
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/tx/total
```

Expected Response:
```cmd
StatusCode        : 200
StatusDescription : OK
Content           : 81080
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 30
                    ratelimit-remaining: 27
                    ratelimit-reset: 16
                    connection: close
                    Content-Length: 5
                    Content-Type: application/json; charset=utf-8...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 30], [ratelimit-remaining, 27],
                    [ratelimit-reset, 16]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 5
```