# TelegramLuaBot v2
-------
This is a telegram bot based on the Telegram API and GroupButler for chatting with users which got reported in Telegram.
----
#Help
-------
In private:


/a <message>  -This will send a message to the admin.

/u <pm> (VIA REPLY) - This will send a reply to the user/sender.


Admin commands:


/blacklist <userid> -This will block the user to send messages. (using id)

/blacklist <username> -This will block the user to send messages. (using username)

/whitelist <userid>  -This will unblock the user to send messages. (using id)

/whitelist <username>  -This will unblock the user to send messages. (using username



Atterntion!

you can unblock user, by sending /blacklist <userid> or /blacklist <username> twice!
--------------------------------
 Get Started
You **must** have Lua (5.2+), LuaSocket, and LuaSec installed.
-------------------------------
How to install LuaRocks:
```bash
# Download and install LuaSocket and LuaSec

 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz
 tar zxpf luarocks-2.2.2.tar.gz
 cd luarocks-2.2.2
 ./configure; sudo make bootstrap
 sudo luarocks install luasocket
 sudo luarocks install luasec
 cd ..
```
----------------------------
Then GitClone the github repository:
```bash
# Clone the repo

 git clone https://github.com/ThisIsArman/TelegramLuaBot.git
 cd TelegramLuaBot
```
---------------------------
# Admins
**Bot Need To Know Where To Send Pms To?**
**Open config.lua in a text editor and Do the following changes:**
> • Make sure that privacy is disabled, otherwise the bot won't see replied messages unless they starts with '/'. Write `/setprivacy` to [BotFather](http://telegram.me/BotFather) to check the current setting.
>
> • Set bot_api_key to the authentication token you received from the [BotFather](http://telegram.me/BotFather).
>
> • Set admin as your Telegram ID.
------------------------
To start the bot, run `bash launch.sh`. To stop the bot, press Ctrl+c twice.

You may also start the bot with `lua bot.lua`, but then it will not restart automatically.
-----------------------
##Contributors
Everybody is free to contribute to TelegramLuaBot.

The creator who created This Bot is [Arman](http://github.com/thisisarman). He can be contacted via [Telegram](http://telegram.me/thisisarman) .
Special Thanks To


The creator and maintainer of otouto is [topkecleon](http://github.com/topkecleon). He can be contacted via [Telegram](http://telegram.me/topkecleon), [Twitter](http://twitter.com/topkecleon), or [email](mailto:topkecleon@outlook.com).

The kanger who created group butler :[Telegram](http://telegram.me/Rlotar).









-----------------------

