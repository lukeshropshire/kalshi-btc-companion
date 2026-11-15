

<!DOCTYPE html>

<html>

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Kalshi BTC Companion</title>

<style>

body {

  background:#101827;

  color:white;

  font-family:Arial;

  padding:24px;

}

h1 { color:#55d6a5; }

.panel {

  background:#1d293b;

  padding:18px;

  border-radius:12px;

  margin-top:18px;

}

button {

  padding:12px 20px;

  border:0;

  border-radius:8px;

  background:#55d6a5;

  font-weight:bold;

}

</style>

</head>

<body>

<h1>Kalshi BTC Companion</h1>

<p>15-minute Bitcoin market connection test</p>

<div class="panel">

  <h3>Kalshi Connection</h3>

  <p id="status">Connecting...</p>

  <p id="market"></p>

  <p id="prices"></p>

  <button onclick="loadMarket()">Refresh</button>

</div>

<script>

async function loadMarket() {

  const status = document.getElementById("status");

  const market = document.getElementById("market");

  const prices = document.getElementById("prices");

  status.textContent = "Connecting to Kalshi...";

  market.textContent = "";

  prices.textContent = "";

  try {

    const url =

      "https://api.elections.kalshi.com/trade-api/v2/markets?series_ticker=KXBTC15M&status=open&limit=100";

    const response = await fetch(url);

    if (!response.ok) throw new Error("HTTP " + response.status);

    const data = await response.json();

    const markets = data.markets || [];

    if (!markets.length) {

      status.textContent = "Connected, but no open BTC markets found.";

      return;

    }

    const m = markets[0];

    status.textContent = "CONNECTED";

    market.textContent =

      m.title + " | " + m.ticker;

    prices.textContent =

      "YES bid: $" + m.yes_bid_dollars +

      " | YES ask: $" + m.yes_ask_dollars +

      " | NO bid: $" + m.no_bid_dollars +

      " | NO ask: $" + m.no_ask_dollars;

  } catch (error) {

    status.textContent = "Connection failed: " + error.message;

  }

}

loadMarket();

</script>

</body>

</html>
