# arbitrum:eth\_newBlockFilter \\\[WebSocket\\]

#### Parameters

\-

#### Request

```java
wscat -c wss://arbitrum.getblock.io/YOUR-API-KEY/mainnet/ 
# wait for connection and send the request body 
{"jsonrpc": "2.0",
"method": "eth_newBlockFilter",
"params": [],
"id": "getblock.io"}
```

#### Response

```java
{
    "id": "getblock.io",
    "jsonrpc": "2.0",
    "result": "0xeb08bb14189d86964c8f4e8ab2730e30"
}
```
