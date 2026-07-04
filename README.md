# Crypto-Tracker

I built this iOS app to watch live cryptocurrency prices update in real time, mostly as a way to practice Swift and working with a REST API. It shows major crypto prices refreshing every second in both US dollars and Canadian dollars.

The data comes from the CoinGecko REST API, and the app re-fetches it once per second so the numbers stay current. Switching which currencies are displayed only takes a couple of lines in the parsing code.

### Gif#1: Live prices refreshing every second
##### The app calls the CoinGecko API on a one-second timer and updates each label whenever new JSON data comes back.
<p align="center">
  <img src="http://g.recordit.co/Vpw6o6F4to.gif" alt="animated" />
</p>

<br>
<br>

### Gif#2: Prices shown in USD and CAD
##### The same API response is parsed to display each value in both US and Canadian dollars.
<p align="center">
  <img src="http://g.recordit.co/dsTfVDo5AN.gif" alt="animated" />
</p>
