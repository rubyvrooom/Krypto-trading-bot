```c++
#include <iostream>

int main()
{
  std::cout << "Hello World! did you know?";
}
```
<p align="center"><img src="https://user-images.githubusercontent.com/1634027/32386807-b0bd1808-c0c2-11e7-9d98-9cb28e6fd51d.jpg" /></p>
<p align="center"><img src="https://user-images.githubusercontent.com/1634027/31733764-e79df244-b43c-11e7-9186-92b6744db290.png" /></p>
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
<p align="center">I am from a country that is certainly old,<br />
It has been a long time forgotten and oppressed.<br />
<br />
I am from a country where fear is called sanity,<br />
that walks one step forward and two backwards.<br />
<br />
I am from a country that slowly breaks down,<br />
and between illusions and frustrations goes forth.<br /><br />
<img src="https://user-images.githubusercontent.com/1634027/32696081-78efb9dc-c76e-11e7-87df-f67db7cbfda8.jpg" /><br />Our battle? freedom, democracy and peace.<br />We will never surrender.<br /><br />There is no jail, prision guard, lock or court decision<br />that can, if we do not want it to, deprive ourselves of begin the way we are.</p>
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
<p align="center"><img src="https://user-images.githubusercontent.com/1634027/31734164-1ab05c66-b43e-11e7-9e52-3fd874045876.jpg" /></p>
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />

<p align="center">yet Today, is a beautiful day.<br/><br/><a href="https://www.youtube.com/embed/BK7DIJq4slg"><img src="https://user-images.githubusercontent.com/1634027/33692212-60b1ad80-daec-11e7-8875-93d0a39813e3.png" /></a></p>


[***REFUGEES WELCOME!***](http://www.refugeesaid.eu/rab-campaign/)

[![Release](https://img.shields.io/github/release/ctubio/Krypto-trading-bot.svg)](https://github.com/ctubio/Krypto-trading-bot/releases)
[![Platform](https://img.shields.io/badge/platform-unix--like-lightgray.svg)](https://www.gnu.org/)
[![g0t0 Counter](https://tinyurl.com/g0t0search)](https://tinyurl.com/g0t0docs)
[![Software License](https://img.shields.io/badge/license-ISC-111111.svg)](https://raw.githubusercontent.com/ctubio/Krypto-trading-bot/master/LICENSE)
[![Software License](https://img.shields.io/badge/license-MIT-111111.svg)](https://raw.githubusercontent.com/ctubio/Krypto-trading-bot/master/COPYING)

[`K.sh`](https://github.com/ctubio/Krypto-trading-bot) is a very low latency [market making](https://github.com/ctubio/Krypto-trading-bot/blob/master/MANUAL.md#what-is-market-making) trading bot with a full featured [web interface](https://github.com/ctubio/Krypto-trading-bot#web-ui), it directly connects to [several cryptocoin exchanges](https://github.com/ctubio/Krypto-trading-bot#compatible-exchanges). On a decent machine reacts to market data by placing and canceling orders in under milliseconds.

### <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4be.png" align="middle" /> Latest version at https://github.com/ctubio/Krypto-trading-bot <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f51e.png" align="middle" /> <img src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4b8.png" align="middle" />

[![Build Status](https://img.shields.io/travis/ctubio/Krypto-trading-bot/master.svg?label=test%20build)](https://travis-ci.org/ctubio/Krypto-trading-bot)<!--[![Coverage Status](https://img.shields.io/coveralls/ctubio/Krypto-trading-bot/master.svg?label=code%20coverage)](https://coveralls.io/r/ctubio/Krypto-trading-bot?branch=master)
[![Quality Status](https://img.shields.io/codacy/grade/d48a59c313504f7988e3df031665f90f/master.svg)](https://www.codacy.com/app/ctubio/Krypto-trading-bot)-->
[![Last Commit](https://img.shields.io/github/last-commit/ctubio/Krypto-trading-bot.svg)](https://github.com/ctubio/Krypto-trading-bot)
[![Dependency Status](https://img.shields.io/david/ctubio/Krypto-trading-bot.svg)](https://david-dm.org/ctubio/Krypto-trading-bot)
[![Open Issues](https://img.shields.io/github/issues/ctubio/Krypto-trading-bot.svg)](https://github.com/ctubio/Krypto-trading-bot/issues)
[![Open Issues](https://img.shields.io/github/issues/ctubio/tribeca.svg)](https://github.com/ctubio/tribeca/issues)
[![Downloads Last 21 Commits](https://img.shields.io/github/downloads/ctubio/Krypto-trading-bot/total.svg?label=downloads%20last%2021%20commits)](https://github.com/ctubio/Krypto-trading-bot)

Runs on unix-like systems. Persistence is achieved using a built-in server-less SQLite C++ interface. Installation via Docker is supported, but manual installation in a dedicated [Debian](https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/) (or [Raspbian](https://www.raspberrypi.org/downloads/raspbian/)) or [CentOS](https://wiki.centos.org/Download) instance is recommended.

![Web UI Preview](https://raw.githubusercontent.com/ctubio/Krypto-trading-bot/master/etc/img/web_ui_preview.png)

The web UI is compatible with most web browsers/devices/resolutions, but Firefox or Chrome at 1600px are recommended. Doesn't require configuration of any web server (unless installed behind your own reverse proxy).

### Compatible Exchanges

||with Post-Only Orders support|without Post-Only|
|---|---|---|
|**without Maker fees**|[Coinbase GDAX](https://www.gdax.com/)<br> &#10239; _REST + WebSocket + FIX_|[HitBTC](https://hitbtc.com/)<br> &#10239; _REST + WebSocket_<br><br>|
|**with Maker and Taker fees**|[Bitfinex](https://www.bitfinex.com/)<br> &#10239; _REST + WebSocket_<br><br>[Kraken](https://www.kraken.com/) (under development)<br> &#10239; _REST_<br><br>[Poloniex](https://www.poloniex.com/) !!see [#284](https://github.com/ctubio/Krypto-trading-bot/issues/284)<br> &#10239; _REST_|[OKCoin.com](https://www.okcoin.com/)<br>[OKCoin.cn](https://www.okcoin.cn/)<br>[OKEx.com](https://www.okex.com/)<br> &#10239; _REST + WebSocket_<br><br>[Korbit](https://www.korbit.co.kr/)<br> &#10239; _REST_|

All currency pairs are supported.

## README
- Documentation
  - [README](#readme)
  - [MANUAL](https://github.com/ctubio/Krypto-trading-bot/blob/master/MANUAL.md)
- Installation
  - [Docker Installation](#docker-installation)
  - [Manual GIT Installation](#manual-git-installation)
  - [Manual ZIP Installation](#manual-zip-installation)
  - [After Manual Installation](#after-manual-installation)
  - [Upgrade to the latest commit](#upgrade-to-the-latest-commit)
  - [Multiple instances party time](#multiple-instances-party-time)
- Information
  - [Compatible Exchanges](#compatible-exchanges)
  - [Configuration](#configuration)
  - [Application Usage](#application-usage)
  - [Web UI](#web-ui)
  - [Databases](#databases)
  - [Charts](#charts)
  - [Cloud Hosting](#cloud-hosting)
- Development
  - [XMR miner](#xmr-miner)
  - [Test units and Build notes](#test-units-and-build-notes)
  - [Unreleased Changelog](#unreleased-changelog)
  - [Release 3.0 Changelog](#release-30-changelog)
  - [Release 2.0 Changelog](#release-20-changelog)
  - [Release 1.0 Changelog](#release-10-changelog)
- Humans and Milk Mammals
  - [Unlock](#unlock)
  - [Donations](#donations)
  - [Very Special Thanks](#very-special-thanks-to)
  - [Help](#help)
  - [Issues](#issues)
  - [Votes](#votes)

### Docker Installation

See [etc/Dockerfile](https://github.com/ctubio/Krypto-trading-bot/tree/master/etc#dockerfile) section if you use winy (because the Manual Installation only works on unix-like platforms).

### Manual GIT Installation

0. Ensure you agree to install collaborative non-free software (see [Unlock](#unlock) section).

1. Ensure your target machine has installed `git`, `make` and `vim`.

2. Run in any location that you wish (feel free to customize the suggested folder name K):
```
 $ git clone ssh://git@github.com/ctubio/Krypto-trading-bot K
 $ cd K
 $ make install
 $ vim K.sh
```

To upgrade anytime see [Upgrade to the latest commit](#upgrade-to-the-latest-commit) section.

### Manual ZIP Installation

0. Ensure you agree to install collaborative non-free software (see [Unlock](#unlock) section).

1. Ensure your target machine has installed `curl`, `make` and `vim`.

2. Run in any location that you wish (feel free to customize the suggested folder name K):
```
 $ mkdir K
 $ cd K
 $ curl https://raw.githubusercontent.com/ctubio/Krypto-trading-bot/master/Makefile > Makefile
 $ make install
 $ vim K.sh
```

To upgrade anytime just run `make reinstall`.

### After Manual Installation

See [configuration](#configuration) section while setting up the configuration options in your new config file `K.sh`.

Once the config file is ready, it can be executed simply like:
```
 $ ./K.sh
```

Alternatively use `make start` to run `K.sh` in the background using [screen](https://www.decf.berkeley.edu/help/unix/screen.html) (to see the output, attach the screen with `make screen` [or run all at once with `make start screen`]).

Feel free to run `make stop` or `make restart` anytime, and don't forget to [read the fucking manual](https://github.com/ctubio/Krypto-trading-bot/blob/master/MANUAL.md).

Troubleshooting:

 * If there is no wallet data on a given exchange, do a manual buy/sell order first using the website of the exchange.

 Optional:

 * See `./K.sh --help` and `make help`.

 * Replace the certificate at `etc/sslcert` folder with your own, see [web ui](https://github.com/ctubio/Krypto-trading-bot#web-ui) section. But, the certificate provided is a fully featured default openssl, that you may just need to authorise in your browser.

### Configuration

See [etc/K.sh.dist](https://github.com/ctubio/Krypto-trading-bot/blob/master/etc/K.sh.dist) file or your own `./K.sh` file.

It just contains a few variables with examples ready to be reused (the suggested urls will work), and at the very end of the file is the execution of the bot.

### Upgrade to the latest commit

After each reinstall, `make restartall` will be executed automatically.

To upgrade under Manual ZIP Installation, please run `make reinstall`.

To upgrade under Manual GIT Installation:

Feel free anytime to check if there are new modifications with `make diff`.

Once you decide that is time to upgrade, execute `make latest` to download and install the latest modifications in your remote branch (or directly `make reinstall` to skip the validation of the new commit messages).

`git` commands do not upgrade nothing because do not compile nothing (if you update the source with git, then later consider to recompile the source or run `make reinstall`).

### Multiple instances party time

Please note, an "instance" is in fact a `*.sh` config file located in the top level path; using a single machine and the same source folder, you can run as many instances as `*.sh` files you have in the top level path (limited by the available free RAM).

Anytime you can list the current instances running with `make list`.

Simple commands like `make start`, `make screen`, `make stop` or `make restart` (without any config file defined) will use the default config file `K.sh`.

To run multiple instances using a collection of config files:

1. Create a new config file with `cp etc/K.sh.dist X.sh && chmod +x X.sh` (use `X.sh` or any name but keep `.sh` extension).

2. Edit the new config file as you alternatively desire.

3. Run the new instance with `./X.sh` or `K=X.sh make start`, also the commands `make screen`, `make stop` and `make restart` allow the environment variable `K`, the value is simply the filename of the config file that you want to run; this value will also be used as the `uid` of the process executed by `screen`.

4. Open in the web browser the different pages of the ports of the different running instances, or display the UI of all instances together in a single page using the MATRYOSHKA link in the footer (that can be predefined using the optional argument `--matryoshka=URL`).

After multiple config files are setup, to control them all together instead of one by one, the commands `make startall`, `make stopall` and `make restartall` are also available, just remember that config files with a filename starting with underscore symbol "_" will be skipped.

### Application Usage

1. Open your web browser to connect to HTTPS port `3000` (or your configured port number) of the machine running K. If you're running K locally on Mac/Windows on Docker, replace "localhost" with the address returned by `boot2docker ip`.

2. Read up on how to use K and market making in the [manual](https://github.com/ctubio/Krypto-trading-bot/blob/master/MANUAL.md).

3. Set up trading parameters to your liking in the web UI. Click the "BTC/USD" button so it is green to start making markets.

### Web UI

Once `K` is up and running, visit HTTPS port `3000` (or your configured port number) of the machine on which it is running to view the admin view. There are inputs for quoting parameters, grids to display market orders, market trades, your trades, your order history, your positions, and a big button with the currency pair you are trading. When you're ready, click that button green to begin sending out quotes. The UI uses a healthy mixture of socket.io and angularjs observed with reactivexjs.

If you want to generate your own certificate see [SSL for internal usage](http://www.akadia.com/services/ssh_test_certificate.html).

In case you really want to use plain HTTP, use `--without-ssl` argument.

### Databases

Each currency pair of each exchange will use a different sqlite database file.

All database files are located at `/data/db/K.*.db`, where `*` is the identifier with format `exchange.base_currency.quote_currency`; it is located outside the application path to survive reinstalls and wild `rm -rf path/to/K`.

You can copy any `.db` file to another machine when migrating or as a backup.

If a database file do not exists, the application will create it on boot; otherwise, it will load it and reuse it.

To see the data of each database file you can use https://github.com/sqlitebrowser/sqlitebrowser or similars.

To set a different database path or to set an [in-memory database](https://sqlite.org/inmemorydb.html), use `--database=PATH` argument (see `--help`).

### Charts

The metrics are not saved anywhere, is just UI data collected with a visibility retention of 6 hours, to display over time:

 * Market Fair Value with High and Low Prices
 * Trades Complete
 * Target Position for BTC currency (TBP)
 * Target Position for Fiat currency
 * STDEV and EWMA values for Quote Protection and APR
 * Amount available in wallet for buy
 * Amount held in open trades for buy
 * Amount available in wallet for sell
 * Amount held in open trades for sell
 * Total amount available and held at both sides in BTC currency
 * Total amount available and held at both sides in Fiat currency

### Cloud Hosting

If you ask me, [<img height="20px" src="https://user-images.githubusercontent.com/1634027/29756933-3e64c62e-8ba8-11e7-916a-3b0ae1481a52.png">](https://www.dreamhost.com/r.cgi?475987/cloud/) is a very nice web hosting company (awesome support team, awesome servers). Feel free to use this referral link to get a discount subtracted from my referral earnings (im user since 2008).

### XMR miner

Because testing requires coins (or patience), the UI have included a XMR miner to generate coins, but is disabled by default.

Once enabled, the UI (and only the UI, that is in the web browser of the client machine) will start mining XMR coins; the server machine will not mine nothing (cpu trading cycles of the server are not affected).

Is there because i use it, but you can run it too if you decide to collaborate with the development of both XMR and K.

In the other side (in the server side), there is also a disabled by default XMR miner (see `--free-version` argument at [Unlock](#unlock) section).

### Test units and Build notes

Make sure your build machine has installed [node](https://nodejs.org/en/download/package-manager/), and also ensure `make dist` provides all dependencies without errors.

Then, feel free to run `make test` anytime.

To rebuild the application with your modifications, see `make help` and choose a target.

To pipe the output to stdout, execute the application in the foreground with `./K.sh --naked`.

To ignore the output, execute the application in the background with `screen -dmS K K.sh` or with the alias `make start` or simply `./K.sh`.

For more information consider to follow the *white rabbit*, but its dangerous to go alone, take this:

c sandbox: [wandbox.org](https://wandbox.org)

js sandbox: [jsfiddle.net](https://jsfiddle.net)

ws sandbox: [websocket.org](https://www.websocket.org/echo.html)

### Unreleased Changelog:

nothing yet

### Release 4.0 Changelog:

Updated HitBTC API v2.

Added ZIP installation steps for non-git-lovers.

Added HamelinRat quoting mode and Trend safety thanks to b-seite and serzhiio contributions.

Added XMR network ecosystem optional support.

Added command-line arguments.

Updated quoting engine and gateways without nodejs.

Added Makefile to replace npm scripts.

~~Added PNG files as configuration files.~~

Added built-in C++ WWW Server to replace expressjs and socketio.

Added built-in SQLite C++ interface to replace external mongodb server.

Added Poloniex API.

### Release 3.0 Changelog:

Updated application name to K because of Kira.

Added nodejs7, typescript2, angular4 and reactivexjs.

Added cleanup of bandwidth, source code, dependencies and installation steps.

Added many quoting parameters thanks to Camille92 genius suggestions.

Added support for multiple instances/config files with nested matryoshka UI.

Added npm scripts, david-dm, travis-ci, coveralls and codacy.

Added historical charts to replace grafana.

Added C++ math functions.

Updated OKCoin API (since https://www.okcoin.com/t-354.html).

Updated Bitfinex API v2.

Added GDAX FIX API with stunnel.

Added Korbit API.

### Release 2.0 Changelog:

Added new quoting styles PingPong, Boomerang, AK-47.

Added cleanup of database records, memory usage and log recording.

Added audio notices, realtime wallet display, and grafana integration.

Added https, dark theme and new UI elements.

Added a bit of love to Kira.

### Release 1.0 Changelog:

see the upstream project [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca).

### Unlock

The bot is unlocked for collaborators and contributors (feel free to make acceptable Pull Requests for already opened issues or for anything you consider useful, and to let me know in the description of the PR the BTC Payment Address displayed in the bot that you wish to unlock, and i will credit it for you).

Meanwhile locked, market levels are limited (only are used the first 3 price levels); once unlocked the bot reads the full list of market levels (up to thousands) from the exchange.

Anonymous users can also unlock any API Key but is required a payment of 0.01210000 BTC to the address displayed in the UI of the bot, once unlocked feel free to use different currency pairs or reinstall in a different machine but keep the same unlocked API Key (changing the API Key will lock or unlock again the bot).

Alternatively use `--free-version` argument to anonymously unlock any API Key and avoid the payment; all market levels will be visible and usable but not in realtime, instead will be slowdown around 3 seconds with a [XMR mining calculation](https://github.com/monero-project/monero/blob/master/src/crypto/hash.c#L42) of 21 hashes (if any hash meets the current XMR network target it will be send to my XMR pool for my fun and profit).

Otherwise if you choose to not support further development by ctubio, just keep running some old commit and do not upgrade (prior v3.0 was all unlocked).

### Donations

nope, this project doesn't have maintenance costs. but you can donate to your favorite developer today! (or tomorrow!)

or see the upstream project [michaelgrosner/tribeca](https://github.com/michaelgrosner/tribeca).

or donate your time with programming or financial suggestions in the topical IRC channel [##tradingBot](https://kiwiirc.com/client/irc.domirc.net:6697/?theme=cli##tradingBot) at irc.domirc.net on port 6697 (SSL), or 6667 (plain) or feel free to make any question, but questions technically are not donations.

### Very Special Thanks to:

- https://github.com/michaelgrosner/tribeca (https://github.com/michaelgrosner)
- https://curl.haxx.se (https://github.com/bagder)
- https://github.com/michaelgrosner/tribeca (https://github.com/michaelgrosner)
- https://github.com/uNetworking (https://github.com/alexhultman)
- https://github.com/michaelgrosner/tribeca (https://github.com/michaelgrosner)
- https://nlohmann.github.io/json (https://github.com/nlohmann)
- https://github.com/michaelgrosner/tribeca (https://github.com/michaelgrosner)
- http://invisible-island.net
- https://github.com/michaelgrosner/tribeca (https://github.com/michaelgrosner)
- https://www.sqlite.org
- https://github.com/michaelgrosner/tribeca (https://github.com/michaelgrosner)

### Help

If you need installation or usage support contact me at [earn.com/analpaper](https://earn.com/analpaper/) (non-free high-priority service).

### Issues

To request new features open a [new issue](https://github.com/ctubio/Krypto-trading-bot/issues/new?title=Feature%20request) and explain your improvement as you consider.

To report errors open a [new issue](https://github.com/ctubio/Krypto-trading-bot/issues/new?title=Error%20report) only after collecting all possible relevant log messages.

Pull Requests are welcome, but adhere to the Contributor License Agreement:
- Your biological and technological distinctiveness will be added to our own. Resistance is futile.

### Votes

What exchange you don't want to be deleted from the bot?

[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/GDAX)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/GDAX/vote)
[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Bitfinex)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Bitfinex/vote)
[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/OkCoin)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/OkCoin/vote)
[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/HitBTC)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/HitBTC/vote)
[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Korbit)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Korbit/vote)
[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Poloniex)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Poloniex/vote)
[![](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Delete%20all%2C%20my%20exchange%20is%20none%20of%20these.)](https://m131jyck4m.execute-api.us-west-2.amazonaws.com/prod/poll/01BPF861CD0EVTZHPF0JJ7TZQJ/Delete%20all%2C%20my%20exchange%20is%20none%20of%20these./vote)

### like yesterday, since 0day and ∞

![bcn](https://user-images.githubusercontent.com/1634027/29495722-1d924018-85c5-11e7-8d61-d83f5716ae9e.jpg)

### every new day we sing:

 - https://www.youtube.com/watch?v=g--fsK6aLf8
 - https://www.youtube.com/watch?v=SS9DJX8gTKk
 - https://www.youtube.com/watch?v=Rom4qWtEkMA
 - https://www.youtube.com/watch?v=wXHm9Yl5tRM
 - https://www.youtube.com/watch?v=xPg_e_3cK-E
 - https://www.youtube.com/watch?v=KKpcQIfIAi8
 - https://www.youtube.com/watch?v=lwspxyzOfkY
 - https://www.youtube.com/watch?v=pZAmer0EmMQ
 - https://www.youtube.com/watch?v=50aXt1ctmUU
 - https://www.youtube.com/watch?v=vofff0Ei3kk
 - https://www.youtube.com/watch?v=4Ois3zB7SJ4
 - https://www.youtube.com/watch?v=1rNT0paAGTs
 - https://www.youtube.com/watch?v=_wGDcWD1E1A
 - https://www.youtube.com/watch?v=DVg2EJvvlF8
 - add your song here (please open a [new issue](https://github.com/ctubio/Krypto-trading-bot/issues/new?title=Today,%20I%20sing) to share your link)
<p align="center"><!----><img src="https://user-images.githubusercontent.com/1634027/32134633-642bb47a-bbf1-11e7-809c-f2d4d57678e0.jpg" />
<br /><br /><br /><br /><br /><br /><br />
<img src="https://user-images.githubusercontent.com/1634027/32695988-22681724-c76b-11e7-8557-7f2b15b2686b.jpg" />
<br /><br /><br /><br />Violence should not be the answer to those who<br />are asking for freedom.<br /><!----><br /><br /><br /><br />
<img src="https://user-images.githubusercontent.com/1634027/29746351-7478d556-8ad7-11e7-8b27-445eefa8f960.jpg" />
<br /><br /><br /><br /><br /><br /><br /><br /><br />
<img width="300" src="http://hits.dwyl.io/ctubio/Krypto-trading-bot.svg" /></p>
