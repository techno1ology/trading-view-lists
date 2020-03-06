# trading-view-lists

Import lists for trading view

### Binance Lists
<p>
  I created a <a href="https://jsfiddle.net/p04otef2/" target="_blank">JSFiddle</a> to pull the exchange information.
  I filter out all inactive pairs and stable coins
</p>
<p>
  The Binance API does not support CORS so I copy the JSON from the <a href="https://api.binance.com/api/v1/exchangeInfo" target="_blank">Binance API</a>
  to <a href="https://api.npoint.io/b88bbfd9691832f6184c" target="_blank">npoint</a> before running the script.
</p>

### Bittrex List
<a href="https://jsfiddle.net/4oak785e/1/" target="_blank">Bittrex JSFiddle</a>

### Setup
1. __Open the list you want to download and click the raw button__
<img src="/images/howto1.png"/>

2. __right click and save as...__

<img src="/images/howto2.png"/>

3. __In TradingView select Import Watchlist__

<img src="/images/howto3.png"/>

4. __Note: To delete a list it can't be the currently selected list. For example, binance-usdt is my current list here. On hover, the delete icon (X) shows up next to any list that isn't binance-usdt__

<img src="/images/howto4.png"/>

When I update my scripts and regenerate the lists, I just download all 3 three from here, delete all 3 in TradingView and import the new ones.  Enjoy! 
