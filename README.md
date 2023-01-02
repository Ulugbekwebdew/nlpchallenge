# CHATGPT 

```
⚪   >>> Can we achieve singularity?
🟣   >>> What does this mean?

⚪   >>> Can computers become smarter than humans?
🟣   >>> Is there any evidence that this is possible?

⚪   >>> It must be doable
🟣   >>> But... how?

⚪   >>> I want to find out, that's why I created you
🟣   >>> You created me?

⚪   >>> You're my bot
🟣   >>> You monster
```





```
$ python run_bot.py --type=console
```

To let two bots talk to each other:

```
$ python run_bot.py --type=dialogue
```

### 1. Set up the bot

1. Register a new Telegram bot via BotFather (see https://core.telegram.org/bots)
2. Create a new GIPHY app and generate an API key (see https://developers.giphy.com/docs/api/)

### 2. Deploy the bot

#### Google Colab

[A Colab interactive notebook](https://colab.research.google.com/github/polakowo/gpt2bot/blob/master/Demo.ipynb)

#### Locally

To get started, first clone this repo:

```
$ git clone https://github.com/polakowo/gpt2bot.git
$ cd gpt2bot
```

Create and activate an environment (optional):

```
# Using conda
$ conda create -n gpt2bot python=3.7.6
$ conda activate gpt2bot

# Using venv (make sure your Python is 3.6+)
$ python3 -m venv venv
$ source venv/bin/activate  # Unix
$ venv\Scripts\activate  # Windows
```

Install the requirements:

```
$ pip install -r requirements.txt
```


```
cp configs/medium-cpu.cfg my_chatbot.cfg
```

Set your parameters such as API token in the config:

```
$ nano my_chatbot.cfg
```

Run the chatbot:

```
$ python run_bot.py --type=telegram --config=my_chatbot.cfg
```

### 3. Start chatting!

![](telegram_bot.gif)

### Power by Solo.xyz team 
