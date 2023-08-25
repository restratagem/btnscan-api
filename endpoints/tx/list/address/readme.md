# /tx/list/:address

Returns the latest transactions of an address. Limited to a maximum of 150 transactions.

## Endpoint

**Method:** `GET`  
**Response Type:** `application/json`  
**Response Format:** JSON  

Syntax:

```
https://btn.api.restratagem.com/tx/list/:address
```
*Replace `:address` with the wallet address you want to query.*

🟢 Try Live:
https://btn.api.restratagem.com/tx/list/0x811f227d4bf85b48b971057e9d913b11511a25ac


## Usage Example

### Browser

Input:
```
https://btn.api.restratagem.com/tx/list/0x811f227d4bf85b48b971057e9d913b11511a25ac
```

Expected Response:

```json
[
    {
        "id":105652,
        "hash":"0x494498808abdecfec120c18172672cab66ad04722be773adce7761975fe18460",
        "blockNumber":308001,
        "from":"0x811f227d4bf85b48b971057e9d913b11511a25ac",
        "to":"0x020830334e9185f3f56ded1de4628bd005d38a0d",
        "value":"199108466000000000",
        "gasUsed":"0x5208",
        "gasPrice":"0x3b9aca00",
        "status":1,
        "nonce":46378,
        "index":3,
        "smartContract":null,
        "inputData":"0x",
        "timestamp":1693002209
    }
]
```

### cURL

Input:
```
curl https://btn.api.restratagem.com/tx/list/0x811f227d4bf85b48b971057e9d913b11511a25ac
```

Expected Response:
```cmd
StatusCode        : 200
StatusDescription : OK
Content           : [{"id":105652,"hash":"0x494498808abdecfec120c18172672cab66ad04722be773adce7761975fe18460","blockNum
                    ber":308001,"from":"0x811f227d4bf85b48b971057e9d913b11511a25ac","to":"0x020830334e9185f3f56ded1de46
                    28...
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 30
                    ratelimit-remaining: 27
                    ratelimit-reset: 17
                    connection: close
                    Content-Length: 57163
                    Content-Type: application/json; charset=ut...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 30], [ratelimit-remaining, 27],
                    [ratelimit-reset, 17]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 57163
```