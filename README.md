# steemprice

<a href="https://steempriceview.000webhostapp.com/index.html">Live Demo</a>
<br>
<p>
A tool used for displaying current steem price in any global currency that you specify.
</p>

### Implementation:
<p>
Steem Price make use of the free Ticker Widget provided by <a href="https://coinmarketcap.com/">Coin Market Cap</a>. The widget is implemented using javascript and its parameters can be modified.
</p>

### Widget Code:
```javascript
<script type="text/javascript" src="https://files.coinmarketcap.com/static/widget/currency.js"></script><div class="coinmarketcap-currency-widget" data-currency="bitcoin" data-base="USD" data-secondary="" data-ticker="true" data-rank="true" data-marketcap="true" data-volume="true" data-stats="USD" data-statsticker="false"></div>
```
The above code is for the Bitcoin Widget ticker.

- Inorder to change the coin, change the value of **data-currency** from bitcoin to any other coin.
- To change the currency value from USD, change the value of **data-base** from USD to any other currency.
