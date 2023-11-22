# pythoncountdownbot
試験までのスケジュール管理に使う用途に改造したやつ<br>
試験までの残り日数少なくてヤバいわよっ！<br>
![image](https://github.com/Issaimaru/pythoncountdownbot/assets/80198387/1fad1b14-af34-4c3a-9c79-98f9b5a6e949)

## environment
テキトーにreplitで立ち上げてるんですが，結構いいですねこれ<br>
招待リンクは[こちら](https://discord.com/api/oauth2/authorize?client_id=1176812572566114364&permissions=8&scope=bot%20applications.commands)

## Links

**[Discord Support](https://discord.com/invite/b2fY4z4xBY "Join the support guild!")** | **[Invite the Bot](https://top.gg/bot/1015703443358363789)** | **[Patreon](https://www.patreon.com/livecountdownbot)**

## Requirements

For this bot to work, you need at least the following the stuff in requirements.txt. Sure.. I might have missed something, but thats the main stuff at least.

## How to self host

To run this bot yourself? Well, just get the code, install the required stuff, fill in the .env file with your own bot token and you are off.

Well, github is being mean, so you need to create your own .env file. The content should be this:

```
\# .env

DISCORD_TOKEN=YourLongAndComplicatedToken
```

Oh, and then you go into bot.py and edit devservers to be the id of your guild.

After that just run bot.py and you are done!

## History

This bot is a new version of the old Live Countdown made by the legendary _LordBusiness_. Main reason was since the old one didnt have support for slash commands, but discord would go on and require them.
