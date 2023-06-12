# Tickers-symbol

## Resource description
Retrieve current prices and markets

## Request URL
https://api.blockchain.com/v3/exchange/tickers/BTC-USD

## Endpoints and methods
[GET]   /tickers/{symbol}

## Parameters

#### Path parameters
| Parameter | Description | Data type |
|------ | ------ | ------ |
| Symbol | something that stands for or suggests something else | String |

## Request example
curl -X GET "https://api.blockchain.com/v3/exchange/tickers/BTC-USD" -H  "accept: application/json"

## Response body
```json
{
  "symbol": "BTC-USD",
  "price_24h": 25925.37,
  "volume_24h": 24.16596692,
  "last_trade_price": 25925.14
}
```

## Example value
```json
{
  "symbol": "BTC-USD",
  "price_24h": 4998,
  "volume_24h": 0.3015,
  "last_trade_price": 5000
}
```

## Response description
| Response item |	Description |	Data type |
| ------ | ------ | ------ |
| Symbol |	a mark or character used as a conventional representation of an object, function, or process.	| String |
| Price |	the amount of money expected, required, or given in payment for something. |	Integer |
| Volume |	the number of shares traded in a particular stock, index, or other investment over a specific period of time |	Integer |
