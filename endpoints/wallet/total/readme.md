# /wallet/total

Returns the total amount of registered wallets/accounts in the network.

## Endpoint

**Method:** `GET`  
**Response Type:** `application/json`  
**Response Format:** Plain Text  

Syntax:

```
https://btn.api.restratagem.com/wallet/total
```

🟢 Try Live:
https://btn.api.restratagem.com/wallet/total

## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/wallet/total
```

Expected Response:

```json
1446
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/wallet/total
```

Expected Response:
```cmd
StatusCode        : 200
StatusDescription : OK
Content           : 1446
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 30
                    ratelimit-remaining: 28
                    ratelimit-reset: 8
                    connection: close
                    Content-Length: 4
                    Content-Type: application/json; charset=utf-8
                    ...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 30], [ratelimit-remaining, 28],
                    [ratelimit-reset, 8]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 4
```