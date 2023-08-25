# /wallet/top

Returns the top 100 wallets in the network, sorted by balance.

## Endpoint

**Method:** `GET`  
**Response Type:** `application/json`  
**Response Format:** JSON

Syntax:

```
https://btn.api.restratagem.com/wallet/top
```

🟢 Try Live:
https://btn.api.restratagem.com/wallet/top

## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/wallet/top
```

Expected Response (Shortened):

```json
[
    {
        "address":"0x5ccccb6d334197c7c4ba94e7873d0ef11381cd4e",
        "balance":5.328997015744001e+22
    },
    {
        "address":"0xc64b063b70f06da58d8231e3afbc37d8078871f1",
        "balance":2.8754542116379893e+22
    }
]
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/wallet/top
```

Expected Response:
```cmd
StatusCode        : 200
StatusDescription : OK
Content           : [{"address":"0x5ccccb6d334197c7c4ba94e7873d0ef11381cd4e","balance":5.328997015744001e+22},{"address
                    ":"0xc64b063b70f06da58d8231e3afbc37d8078871f1","balance":2.8754542116379893e+22},{"address":"0xa9db
                    5c...
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 30
                    ratelimit-remaining: 29
                    ratelimit-reset: 17
                    connection: close
                    Content-Length: 8662
                    Content-Type: application/json; charset=utf...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 30], [ratelimit-remaining, 29],
                    [ratelimit-reset, 17]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 8662
```