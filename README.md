# Chatbot-for-Stock-market-analysis

This is a working WhatsApp conversational chatbot. This conversational chatbot uses Twilio, Python, and MarketStack. A conversational chatbot on WhatsApp which acts just like your personal finance assistant.

## Technologies Used
1. [Twilio](https://twilio.com) API to send messages to the subscribed bot users
2. [Marketstack](https://marketstack.com/) API which provides stock data of 70+ stock exchanges across the world
3. Python to program the backend processing of the messages using Python and integration of Twilio API and MarketStack API
4. Flask app running on local machine
5. [NGROK](https://ngrok.com/) to create a tunnel to the app from an HTTPS public endpoint

## Python Dependencies Installed
```
pip install certifi
pip install chardet
pip install click
pip install Flask
pip install idna
pip install itsdangerous
pip install Jinja2
pip install MarkupSafe
pip install PyJWT
pip install pytz
pip install requests
pip install six
pip install twilio
pip install urllib3
pip install Werkzeug
```

## Commands for Windows Terminal
1. cd ~/Desktop/bot_stock/bot
2. virtualenv bot
3. Set-ExecutionPolicy Unrestricted
4. bot\scripts\activate
5. SET FLASK_APP=app.py
6. $env:TWILIO_ACCOUNT="-----"
7. $env:TWILIO_TOKEN="-----"
8. $env:MARKETSTACK_KEY="-----"
9. Flask run


