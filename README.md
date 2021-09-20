# Subtitle Translator Bot

Pluggable
[Telegram](https://telegram.org) bot based on
[Pyrogram](https://github.com/pyrogram/pyrogram).

## About the bot

>Simply the purpose of this bot is to translate subtitle files from one language to another.


This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
Mozilla Public License for more details.

### Installation

#### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TharukRenuja/SubtitleTranslator-Bot)


#### The Legacy Way
Simply clone the repository and run the main file:
```sh
git clone https://github.com/TharukRenuja/SubtitleTranslator-Bot

cd SubtitleTranslator-Bot

python3 -m venv venv

. ./venv/bin/activate

pip install -r requirements.txt

python3 bot.py

```
#### Dont forget to edit the creds.py with your own variables like below with your own values
```python3
class cred():
    BOT_TOKEN = "your bot token from botfather"
    API_ID = "your api id from my.telegram.org!"       
    API_HASH = "your api hash from my.telegram.org!"   
    DB_URL = "your database url from google firebase" 
    BOT_NAME = "your bot name"     
```

