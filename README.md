# Telegram Bot Using OpenAI
The Telegram Chatbot with GPT-3.5 Turbo is an intelligent conversational agent designed to interact with users on the popular messaging platform Telegram. Leveraging the cutting-edge capabilities of OpenAI's GPT-3.5 Turbo DSM 1.0 model, this bot can engage users in natural and meaningful conversations, providing responses that are contextually relevant and human-like.


## Prerequisites

To follow this tutorial, you will need:

- Python 3.7 or higher
- A Telegram account and a smartphone
- An OpenAI account and an API key


## Telegram setup:

1. search for botfather
2. /newbot
   - chatgpt88
   - chatgpt88_bot

   Now click on the url


### AIogram docs
https://docs.aiogram.dev/en/latest/

## How to run the code

1. Clone this repository or download the zip file
2. Create a virtual environment and activate it
3. Install the dependencies using `pip install -r requirements.txt`
    > Or alternatively to the above two steps you can run `init_setup.sh` by running the following command in your terminal-
    ```bash
    bash init_setup.sh
    ```
4. Create a `.env` file in the root directory and add your OpenAI API key and Telegram BOT TOKEN as follows:

```ini
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TELEGRAM_BOT_TOKEN=xxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
Python == 3.7.4

5. Run `python src/chatgpt.py` to start the bot
6. Open Telegram and search for your bot username
7. Start a conversation with your bot and enjoy!
