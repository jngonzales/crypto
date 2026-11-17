# CryptoGecko — Live Cryptocurrency Prices

A market view built on the public [CoinGecko](https://www.coingecko.com/en/api)
API: the top coins by market cap in a sortable table, and a chart per coin.

## What it shows

- Rank, name, price, 24h and 7d change, market cap, 24h volume, circulating supply.
- A price chart with 24H, 7D, 30D, 90D and 1Y ranges, drawn with [Chart.js](https://www.chartjs.org/) and a date adapter.
- A coin detail panel with the project description.

## Run it

Open `index.html`.

The page calls the free CoinGecko endpoints directly from the browser, so it
needs a network connection. The public API is rate limited; if the table sits on
"Loading..." after a burst of reloads, wait a minute and refresh.

## Notes

No API key and no backend. All state is fetched on demand.
