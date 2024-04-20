# POKEMON-COORDINATES-TELEGRAM-BOT

## Local Installation

To run this project, you'll need to add the following environment variables to your `.env` file:

`TOKEN`

`DEVELOPER_CHAT_ID`

`BOTHOST`

`DEBUG`

`ADMIN`

`SUPPORT`

`CHAT_ID`

`PERIOD`

Clone the project

```bash
$ git clone https://github.com/chutyhack/pokemon-coordinates-bot.git
```

Navigate to the project directory

```bash
$ cd pokemon-coordinates-bot
```

Create a virtual environment

```sh
$ virtualenv venv
```

Activate the virtual environment

```
# windows
$ source venv/Scripts/activate
# Linux
$ source venv/bin/activate
```

Then install the required libraries:

```sh
(venv)$ pip install -r requirements.txt
```

Once all of that is done, proceed to start the app

```bash
(venv)$ python main.py
```

## Telegram bot's menu

Start sending coordinates with pokemon IV 100:

```bash
  /iv100
```

Start sending coordinates with pokemon IV 90:

```bash
  /iv90
```

Stop sending coordinates:
```bash
  /stop
```

## Demo

[![](https://markdown-videos-api.jorgenkh.no/youtube/JmVROMN3D1s)](https://youtu.be/JmVROMN3D1s "IV 100 Telegram Bot Demo Video")