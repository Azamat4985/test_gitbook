# arbitrum:db\_getHex \\\[WebSocket\\] {disallowed}

#### Parameters

`database` - string

Database name

`key` - string

key name

#### Request

```java
wscat -c wss://arbitrum.getblock.io/YOUR-API-KEY/mainnet/ 
# wait for connection and send the request body 
{"jsonrpc": "2.0",
"method": "db_getHex",
"params": [null, null],
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
