# arbitrum:eth\_accounts \\\[WebSocket\\]

#### Parameters

\-

#### Request

```java
wscat -c wss://arbitrum.getblock.io/YOUR-API-KEY/mainnet/ 
# wait for connection and send the request body 
{"jsonrpc": "2.0",
"method": "eth_accounts",
"params": [],
"id": "getblock.io"}
```

#### Response

```java
{
    "id": "getblock.io",
    "jsonrpc": "2.0",
    "result": []
}
```
