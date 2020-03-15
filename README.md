# zulip-bot
A helloworld bot which replies with "beep boop" to every message @-mentioning it. 


## Setup
Run the following commands from Your root directory

## Step 1
```
git clone https://github.com/spielers/zulip_bot.git  /* To clone this repository */
cd zulip-bot      
virtualenv -p python3 .
source bin/activate
pip install -r requirements.txt
```
## Step 2
```
create keys.yaml file inside root directory and add your secret key in it.
```

## Step 3
```
cd src
python manage.py makemigrations
python manage.py migrate
python manage.py runserver 
``` 

Open http://127.0.0.1:8000/ This will allow you to see the bot in browser
