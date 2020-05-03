![​](https://telegra.ph/file/fe37beee22b97277f97de.jpg)
#  TGFileStream - Telegram Bot 🤖📲

- This is telegram Bot uses Telethon & aiohttp library which asyncronously download files from telegram.
- Get Direct Download Link In a Sec.
- Fastest Telegram Link Generator Bot



## Installing

### 1.  Simple Method

STEP 1: Press 👉🏻 [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)\
STEP 2: get You App credentials from https://my.telegram.org/auth. \
STEP 3: put variable value in the heroku env. variables.\
STEP 4: get environment Variable ( BOT Token ) from BotFather\
STEP 5: Put Heroku_App_URL Variable to your Heroku App Link..\
STEP 5: Boom!.... your done!\


### 2. Legacy Way
Simply clone the repository and run Command In `Python3 -m tgfilestream`:

STEP 1:
```sh
git clone https://github.com/prdpjngd/fileherobot.git
cd fileherobot
virtualenv -p /usr/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt
```
STEP 2: Get You App credentials from https://my.telegram.org/auth \
STEP 3: Put your API ID & API HASH in Config.py file.\
STEP 4: Paste Your Bot Token In Config.py\
STEP 5: Set variable [ Heroku_App_URL ] or [ Server_URL ] to "Localhost"
STEP 6:  Run Command --> `Python3 -m tgfilestream`
STEP 7: Boom your Done...


### How to get your  API ID & API HASH from https://my.telegram.org/auth 👇
```
STEP 1: Login with Your number in international format
STEP 2: Create App & copy API ID & API Hash of your app.
STEP 3: Go to Bot Father in telegram  and create a bot
STEP 4: Generate Bot token and copy to creds.py file.
```

### Variable Explanations ---> these are Mandatory Variables

* `TG_BOT_TOKEN`: Telegram bot token , get from Botfather
* `TG_API_ID`: APP API_ID get this from my.telegram.org
* `TG_API_HASH`: APP API_HASH get this from my.telegram.org
* `Heroku_App_URL`: This is your Heroku app URL.

For example : your Heroku app name is tgfilestream - Then Your URL is -> https://tgfilestream.herokuapp.com
