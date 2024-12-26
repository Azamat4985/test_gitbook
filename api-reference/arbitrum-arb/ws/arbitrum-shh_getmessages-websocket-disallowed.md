# arbitrum:shh\_getMessages \\\[WebSocket\\] {disallowed}

#### Parameters

`id` - string

the filter id.

#### Request

```java
wscat -c wss://arbitrum.getblock.io/YOUR-API-KEY/mainnet/ 
# wait for connection and send the request body 
{"jsonrpc": "2.0",
"method": "shh_getMessages",
"params": [null],
"id": "getblock.io"}
```

#### Response

```java
{
    "result": "null",
    "id": "getblock.io",
    "status_code": 405,
    "message": "Method not allowed"
}
```
