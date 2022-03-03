# **Crypto Prices to Telegram Bot**

Welcome, this is my very first Python script ever, after taking a small course.
The script functions are very simple, as it name indicates, is a script to obtain price of any crypto asset you are interested in, send it to your phone via telegram and save it in an excel spreadsheet file in you computer.

To be able to work properly, the program uses two APIs, which are needed in orther to run correctly.

Please also download the libraries from *requirements.txt* file.

### Telegram API
In order to have your personal **Telegram Bot** sending message to you. You need to create your own bot using the *BotFather* built in bot in the app. 
In order to run the code correctly using the telegram features we need to:
- Create a new *Bot*
- Get the *bot token*
- Obtain the *chat_id*

1. Search for messages or users in Telegram and write *BotFather* 
2. Open a conversation with BotFather and write the command */newbot* and give your new bot a name.
3. Once the bot is created BotFather will provide you with a **token** to access the *HTTP API*.
4. Before getting the **chat_id** it is necessary to start a conversation with the bot. BotFather will give you the link in orther to start the chat with your bot. The chat link will be of the form t.me/{BotName}_bot. Click there and then in the chat you need to write */start* (Only needed one time).
5. To get the **chat_id** you can visit this URL
https://api.telegram.org/botXXX:YYYYY/getUpdates (replace the XXX:YYYYY with your *BOT HTTP API Token* you just got from the Telegram BotFather)
6. Now you have the *token* and the *chat_id*. Paste them in the code.

### Crpytocompare API 
For the puropose of this program (using real-time crypto asset prices, NOTE: maybe not all the  :shit:coins available) the API is not necessary. However, if some user wants to  but it will be explained below in case someone wants to use and improve this code, here is the way to get the API key.

1. Please go to https://min-api.cryptocompare.com/
2. Click in **Get your free API key**
3. API key is free for personal non-commercial projects. Capped at 250,000 lifetime calls.
4. Make an account using any email
5. Go to **APY Keys** tab and create a key (many keys can be generated)
6. Paste the apy key in the code. Use it at your best.

₿ Donations : bc1qx0l3zw79xck3f885qmqnk9drntd4ahj2uz0wfn
