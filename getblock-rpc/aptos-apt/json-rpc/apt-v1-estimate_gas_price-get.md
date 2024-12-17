# apt:/v1/estimate\_gas\_price \\\[GET\\]

#### Parameters

\-

#### Request

```java
curl --location --request GET 'https://apt.getblock.io/v1/estimate_gas_price?' 
--header 'x-api-key: YOUR-API-KEY' 
--header 'Content-Type: application/json' 
```

#### Response

```java
{
    "deprioritized_gas_estimate": 100,
    "gas_estimate": 100,
    "prioritized_gas_estimate": 150
}
```
