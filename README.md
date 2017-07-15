# GTrader-env
[GTrader](https://github.com/gsoros/GTrader) + MySQL + Nginx-SSL

## Requirements
* A recent version of [Docker](https://store.docker.com/search?type=edition&offering=community) and [docker-compose](https://docs.docker.com/compose/install/)

## Installation
1. ```git clone https://github.com/gsoros/GTrader-env.git```
2. ```cd GTrader-env```
3. Optional: edit .env to configure interface and port. E.g. if you want GTrader to listen on all interfaces at the default HTTPS port, enter ```LISTEN_HOST=0.0.0.0``` and ```LISTEN_PORT=443```
2. ```docker-compose up -d```
3. Point your browser to [https://localhost:44333/](https://localhost:44333/)

A default user will have been created with email: ```gtrader@localhost``` and password: ```gtrader```.

After the first log-in GTrader will start fetching candlestick data from the exchanges.

# License
[GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
