# Ziben Yunzuo 10:40 Timer bot (Testing)
Telegram Link: [http://t.me/ziben_yunzuo_bot](http://t.me/ziben_yunzuo_bot)
Audio file removed due to copyrights

## Introduction
This is a [Telegram](https://telegram.org/) bot sending a sticker when it is 10:40 or 22:40.

## Commands
**Start sending stickers:** `/start`

**Stop sending stickers:** `/stop`

**Removed time zone set due to using enviroment** 

**Test the bor answer：** `/ping`

**Start a train manually:** `/trainnow`

*List of timezones in tz database: [https://en.wikipedia.org/wiki/List_of_tz_database_time_zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)*


## Environment
- Node.js 10

## Installation
```sh
npm install
```

## Configuration
Create a file config.json:
```json
{
    "tg_bot_token": "Your Telegram bot token here",
    "log_file": "Log file"
}
```
## Audio Support
Place Opus OGG file in the directory and modify the index

## Start
```sh
npm start
```
