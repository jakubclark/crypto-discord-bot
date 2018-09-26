# Cryptocurrency-Bot
Simple Discord Bot for cryptocurrencies
## Adding this bot to your server
https://discordapp.com/oauth2/authorize?client_id=379728619465080832&scope=bot

Go to this link, select your server and click OK.


# Commands
There are two primary command types supported by this bot:
1) ```!cryptocurrency fiat_currency```

    e.g.: ```!btc eur```
2) ```!cryptocurrency```

    e.g.: ```!eth```

By default, the USD Price of the currency is returned

When in doubt, just use the ```!help``` command!

# Supported Cryptocurrencies and Fiat Currencies

## Cryptocurrencies
* "BTC"
* "BCH"
* "ETH"
* "NGC"
* "XRP"
* "LTC"
* "ETC"
* "DASH"
* "XEM"
* "MIOTA"
* "XMR"
* "BTS"
* "STRAT"
* "EOS"
* "ZEC"
* "BCC"
* "WAVES"
* "NGC

## Fiat Currencies
* "AUD"
* "BRL"
* "CAD"
* "CHF"
* "CNY"
* "EUR"
* "GBP"
* "HKD"
* "IDR"
* "INR"
* "JPY"
* "KRW"
* "MXN"
* "RUB"
* "TRY"
* "USD"

# Running Locally
Install the required packages using ```pipenv install```.

The required python version is 3.6.6

The ```DISCORD_BOT_TOKEN``` Environment Variable must be set to your Discord Bot's Token.
For more info on Discord Bots, [go here](https://discordapp.com/developers/docs/topics/oauth2#bots).

Once set, simply run ```python app.py```.

# Misc.
Originally forked from: https://github.com/efeaydin06/Cryptocurrency-Bot
