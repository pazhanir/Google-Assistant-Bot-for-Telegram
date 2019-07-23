# Google Assistant Bot for Telegram

This is the Google Assistant Bot for Telegram. It's using the [Google Assistant SDK](https://github.com/googlesamples/assistant-sdk-python) 

## Prerequisite
- [a Telegram bot token](https://core.telegram.org/bots#3-how-do-i-create-a-bot)
- [your own Telegram ID (to be your own personal google assistant)](https://github.com/GabrielRF/telegram-id#web-user-id)
- [Reading the Google SDK documentation](https://developers.google.com/assistant/sdk/overview)
- [assistant_helpers.py](https://github.com/googlesamples/assistant-sdk-python/tree/master/google-assistant-sdk/googlesamples/assistant/grpc)
- Little bit of patience

## How to run?
Replace ```YOUR_ID``` with your own ID and ```YOUR_TOKEN``` with the token of the bot.

## Simply run 
```python3 telegramassistant.py --device-id YOUR_DEVICE_ID --device-model-id YOUR_DEVICE_MODEL_ID```
Make sure to replace ```YOUR_DEVICE_ID``` and ```YOUR_MODEL_ID``` with your own. Otherwise it will not work.