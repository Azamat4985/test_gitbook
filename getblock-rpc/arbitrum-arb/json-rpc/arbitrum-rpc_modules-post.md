# arbitrum:rpc\_modules \\\[POST\\]

#### Parameters

\-

#### Request

```java
curl --location --request POST 'https://arbitrum.getblock.io/mainnet/' 
--header 'x-api-key: YOUR-API-KEY' 
--header 'Content-Type: application/json' 
--data-raw '{"jsonrpc": "2.0",
"method": "rpc_modules",
"params": [],
"id": "getblock.io"}'
```

#### Response

```java
{
    "id": "getblock.io",
    "jsonrpc": "2.0",
    "result": {
        "arb": "1.0",
        "debug": "1.0",
        "eth": "1.0",
        "net": "1.0",
        "rpc": "1.0",
        "txpool": "1.0",
        "web3": "1.0"
    }
}
```
