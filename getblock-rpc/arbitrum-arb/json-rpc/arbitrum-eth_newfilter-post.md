# arbitrum:eth\_newFilter \\\[POST\\]

#### Parameters

`Object` - object

Filter options

#### Request

```java
curl --location --request POST 'https://arbitrum.getblock.io/mainnet/' 
--header 'x-api-key: YOUR-API-KEY' 
--header 'Content-Type: application/json' 
--data-raw '{"jsonrpc": "2.0",
"method": "eth_newFilter",
"params": [{"fromBlock": "earliest", "toBlock": "latest", "topics": []}],
"id": "getblock.io"}'
```

#### Response

```java
{
    "id": "getblock.io",
    "jsonrpc": "2.0",
    "result": "0x7a624b4e4688bb09c14e858427d9ede5"
}
```
