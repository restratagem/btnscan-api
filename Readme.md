# BTNScan Public API Endpoints

Use the BTNScan Public API endpoints to fetch live on-chain data from the Bitnet network. Fair usage policy applies, and we reserve the right to close, alter, make unavailable, and reduce the rate limits on the given endpoints at our discretion and with no prior warning. Please use these endpoints at your own risk.

# API Wiki

For easier navigation, we recommend you to use our **[Wiki-formatted version](https://github.com/restratagem/btnscan-api/wiki)** of this library.

## Limits

Rate limits for public usage varies depending on the API servers availability and current usage. The expected average rate limit for most endpoins is of **1 Call Per 15 Seconds** or **4 Calls Per Minute** or **5,760 Calls Per Day**. Security tokens are used for private and enterprise API plans and have higher limits than the public free plan.

## API Server

You can use the `GET` requests method with the public API server below.

```
https://btn.api.restratagem.com/
```

## Endpoints

```
/price
```
Returns the current market price of BTN. [Open ›](/endpoints/price/btn/)

```
/supply
```
Returns the current approximate supply of BTN. [Open ›](/endpoints/supply/btn/)

```
/tx
```
Transaction related responses. [Open ›](/endpoints/tx/)

```
/wallet
```
Wallet related responses. [Open ›](/endpoints/wallet/)

## Usage Example

To fetch the current supply of Bitnet, you can use the public API server with the `/supply` endpoint using `GET`.

### Browser

Input:
```
https://btn.api.restratagem.com/supply/btn
```

Example of Expected Response:
```
317141
```

### cURL

Input:
```cmd
curl https://btn.api.restratagem.com/supply/btn
```

Example of Expected Response:
```cmd
StatusCode        : 200
StatusDescription : OK
Content           : 317141
RawContent        : HTTP/1.1 200 OK
                    access-control-allow-origin: *
                    ratelimit-limit: 5
                    ratelimit-remaining: 3
                    ratelimit-reset: 10
                    connection: close
                    Content-Length: 6
                    Content-Type: application/json; charset=utf-8
                    D...
Forms             : {}
Headers           : {[access-control-allow-origin, *], [ratelimit-limit, 5], [ratelimit-remaining, 3],
                    [ratelimit-reset, 10]...}
Images            : {}
InputFields       : {}
Links             : {}
ParsedHtml        : mshtml.HTMLDocumentClass
RawContentLength  : 6
```