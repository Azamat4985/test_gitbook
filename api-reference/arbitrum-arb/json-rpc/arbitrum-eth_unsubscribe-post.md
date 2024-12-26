# arbitrum:eth\_unsubscribe \\\[POST\\]

#### Parameters

`data` - hex string

A subscription ID previously generated with eth\_subscribe method.

#### Request

```java
curl --location --request POST 'https://arbitrum.getblock.io/mainnet/' 
--header 'x-api-key: YOUR-API-KEY' 
--header 'Content-Type: application/json' 
--data-raw '{"jsonrpc": "2.0",
"method": "eth_unsubscribe",
"params": ["0xe5af64ddfd365b4632988c5935cfedb7"],
"id": "getblock.io"}'
```

#### Response

```java
{
    "error": {
        "code": -32000,
        "message": "subscription not found"
    },
    "id": "getblock.io",
    "jsonrpc": "2.0"
}
```