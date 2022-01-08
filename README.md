https://api.bitforex.com/api/v1/market/ticker?symbol=coin-btc-grin
https://api.bitforex.com/api/v1/market/ticker?symbol=coin-usdt-grin
https://api.gateio.ws/api/v4/spot/tickers?currency_pair=GRIN_USDT
https://api.gateio.ws/api/v4/spot/tickers?currency_pair=GRIN_BTC
https://api.gateio.ws/api/v4/spot/tickers?currency_pair=GRIN_ETH


<div id="results"></div>
	   <script type="text/javascript">
		var apiUrl = 'https://tradeogre.com/api/v1/ticker/BTC-GRIN';
		fetch(apiUrl).then(response => {
		  return response.json();
		}).then(data => {
		  let output = document.getElementById("results");
			output.textContent = data.price ;  // Populate the element
		  console.log(data);
		}).catch(err => {
		  "ERROR"
		});
	    </script>
