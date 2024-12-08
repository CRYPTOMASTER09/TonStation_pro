> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/airdropconfirm97)

# Use Node.Js 18 or later

## Functionality

| Functional                            | Supported |
| ------------------------------------- | :-------: |
| Auto farming                          |    ✅     |
| Claiming task                         |    ✅     |
| Multithreading                        |    ✅     |
| Caching session data                  |    ✅     |
| Using a session/query_id              |    ✅     |
| Binding a proxy to a session/query_id |    ✅     |
| Random sleep time between clicks      |    ✅     |

| Settings                       | Description                                                                |
| ------------------------------ | -------------------------------------------------------------------------- |
| **API_ID / API_HASH**          | Platform data from which to launch a Telegram session (stock - Android)    |
| **AUTO_FARM**                  | Whether the bot should farm (True / False)                                 |
| **AUTO_CLAIM_TASKS**           | Whether the bot claim tasks (True / False)                                 |
| **SLEEP_BETWEEN_REQUESTS**     | Delay between taps in seconds (eg. [200, 700])                             |
| **DELAY_BETWEEN_STARTING_BOT** | Delay between starting in seconds (eg. [20, 30])                           |
| **DELAY_BETWEEN_PAINTING**     | Delay between painting in seconds (eg. [20, 30])                           |
| **DELAY_BETWEEN_TASKS**        | Delay between tasks in seconds (eg. [20, 30])                              |
| **USE_PROXY_FROM_JS_FILE**     | Whether to use proxy from the `bot/config/proxies.js` file (True / False)  |
| **USE_PROXY_FROM_TXT_FILE**    | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

## Installation

You can download [**Repository**](https://github.com/CRYPTOMASTER09/TonStation_pro) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/CRYPTOMASTER09/TonStation_pro.git
~ >>> cd TonStation_pro

#Linux and MocOS
~/TonStation_pro >>> chmod +x check_node.sh
~/TonStation_pro >>> ./check_node.sh

OR

~/TonStation_pro >>> npm install
~/TonStation_pro >>> cp .env-example .env
~/TonStation_pro >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/TonStation_pro >>> node index.js

#Windows
1. Double click on INSTALL.bat in TonStation_pro directory to install the dependencies
2. Double click on START.bat in TonStation_pro directory to start the bot

OR

~/TonStation_pro >>> npm install
~/TonStation_pro >>> cp .env-example .env
~/TonStation_pro >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/TonStation_pro >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/TonStation_pro >>> node index.js --action=1

OR

~/TonStation_pro >>> node index.js --action=2 #session

OR

~/TonStation_pro >>> node index.js --action=3 #query_id

#1 - Create session
#2 - Run clicker
```
