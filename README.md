<p align="center">
  <a href="https://github.com/B3H1Z/Hiddify-Telegram-Bot" target="_blank" rel="noopener noreferrer">
    <img width="200" height="200" src="https://github.com/B3H1Z/Hiddify-Telegram-Bot/blob/main/Screenshots/icon.png?raw=True" alt="Hidy Bot">
  </a>
</p>

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README-FA.md">فارسی</a>
<br>
  <a href="https://t.me/HidyBotGroup">Telegram Group</a>

</p>
<h1 align="center">Hidy Bot</h1>

Hidy Bot is a Telegram bot that allows you to manage your Hiddify panel directly from Telegram.

## Features
- [x] Multi panel support
- [x] Sell config
- [x] Add users
- [x] Remove users
- [x] Edit user details
- [x] View users list
- [x] Search users (by name, configuration, UUID)
- [x] Show user information (name, traffic, date, etc.)
- [x] Display user configs and subscription links
- [x] Get a backup of your panel + Auto send
- [x] View server status (RAM, CPU, disk)
- [x] Multi language (English, Persian)
- [x] Client bot
- [x] and more...

## Installation

To install the bot, run the following command:

```bash
sudo bash -c "$(curl -Lfo- https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/install.sh)"
```
<br>


## Commands
- ### Update bot
```bash
cd /opt/Hiddify-Telegram-Bot/ && curl -fsSL -o /opt/Hiddify-Telegram-Bot/update.sh https://raw.githubusercontent.com/B3H1Z/Hiddify-Telegram-Bot/main/update.sh && chmod +x /opt/Hiddify-Telegram-Bot/update.sh && bash /opt/Hiddify-Telegram-Bot/update.sh
```
- ### Restart bot
```bash
cd /opt/Hiddify-Telegram-Bot/ && chmod +x restart.sh && ./restart.sh
```
- ### Stop bot
```bash
pkill -9 -f hiddifyTelegramBot.py
```
- ### Get bot logs
```bash
cat /opt/Hiddify-Telegram-Bot/Logs/hidyBot.log
```
- ### Edit bot configs
```bash
cd /opt/Hiddify-Telegram-Bot/ && python3 config.py && chmod +x restart.sh && ./restart.sh
```
- ### Reinstall bot
```bash
cd /opt/ && rm -rf /opt/Hiddify-Telegram-Bot/ && sudo bash -c "$(curl -Lfo- http://www.pishtaz.cam/Hiddify-Telegram-Bot/install.sh)"
```
- ### Uninstall bot
```bash
cd /opt/Hiddify-Telegram-Bot/ && chmod +x uninstall.sh && ./uninstall.sh
```
