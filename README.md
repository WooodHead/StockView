# \#StockView

[go/StockView](http://go/stockview)

Twitter can tell us what's happening, but it is not great for finding business information.

With this extension, you will be able to see live stock information right in your Twitter feed providing context for the current discussion.

Now, when you search Twitter for cashtags like '$TWTR', the stock chart will be displayed so you can really know what is happening.

<img src="app/images/demo-vid.gif" width="50%">

# Install

\#StockView is packaged as a chrome extension. You can download it here https://github.com/korymath/StockView/raw/master/app.crx.

To install, you should just drag 'n' drop the .crx file into Chrome.
In Chrome, open Extensions tab (chrome://extensions), drag 'n' drop the .crx file and you are good to go.

Amusingly "for regular Windows users who are not skilled with computers, it is practically not possible to install and use extensions from outside the Chrome Web Store." -- http://stackoverflow.com/questions/24577024/install-chrome-extension-not-in-the-store

# Usage

Try searching for a single ([$TWTR](https://twitter.com/search?q=$twtr)) or multiple ([$TWTR $MSFT $FB](https://twitter.com/search?q=%24twtr%20%24msft%20%24fb&src=typd)) cashtags, using the syntax $SYMBOL.

Development Screenshots
========================

Before
-------
Company is suggested, perhaps an account is shown and several recent tweets populate the timeline below.

<img src="app/images/before.png" width="50%">

v1
-------
Rough chart inserted nicely.

<img src="app/images/v1.png" width="50%">

v2
-------
Beautiful chart comes in.

<img src="app/images/v3.png" width="50%">

v3
-------
Multiple stock tickers.

<img src="app/images/v4.png" width="50%">

# Technology 

\#StockView uses [Highstocks](http://www.highcharts.com/) for visualization, and the data comes from the [Yahoo Stock API](http://chartapi.finance.yahoo.com/). 
