# /wallet/active

Returns the amount of active wallets in the network. The criteria used to determine if a wallet is active or not is having a balance > 0.0009 BTN.

## Endpoint

**Method:** `GET`  
**Response Type:** `application/json`  
**Response Format:** Plain Text

Syntax:

```
https://btn.api.restratagem.com/wallet/active
```

🟢 Try Live:
https://btn.api.restratagem.com/wallet/active

## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/wallet/active
```

Expected Response (Shortened):

```json
869
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/wallet/active
```

Expected Response:
```cmd
StatusCode        : 200
StatusDescription : OK
Content           : 870
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 30
                    ratelimit-remaining: 29
                    ratelimit-reset: 13
                    connection: close
                    Content-Length: 3
                    Content-Type: application/json; charset=utf-8...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 30], [ratelimit-remaining, 29],
                    [ratelimit-reset, 13]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 3
```