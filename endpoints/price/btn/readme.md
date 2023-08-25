# /price/btn

Returns the current price for BTN based on aggregated data from various exchanges.

## Endpoint

**Method:** `GET`  
**Response Type:** Plain Text

## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/price/btn
```

Expected Response:

```
0.590109
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/price/btn
```

Expected Response:
```
StatusCode        : 200
StatusDescription : OK
Content           : 0.590109
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 30
                    ratelimit-remaining: 15
                    ratelimit-reset: 7
                    connection: close
                    Content-Length: 8
                    Content-Type: application/json; charset=utf-8
                    ...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 30], [ratelimit-remaining, 15],
                    [ratelimit-reset, 7]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 8
```