# Telegram FOSS News Bot #

This bot, built over Telegram API is designed to test a subscriber, update model for replacing emails using Telegram.

# MOVED #
While this repository works, it has been forked to [telegram-updates-bot](https://github.com/asdofindia/telegram-updates-bot) to allow building a reusable bot

## Setting up ##
```bash
git clone https://github.com/asdofindia/telegram-fossnewsbot.git
cd telegram-fossnewsbot
mv config.sample.json config.json
vim config.json
# put [bot token and timeout](https://github.com/dar5hak/bub#set) in config.json
# also set the admin id
npm install
mkdir subscribers
```

## Running ##
`node index.js`

Alternatively, consider installing pm2

## Commands on the bot ##
`/start` to subscribe
`/stop` to unsubscribe
`/update message` to send `message` to all subscribers (admin only)
`/stats` for subscriber count (admin only)

## Demo ##
You can subscribe to the original [@fossnewsbot](https://telegram.me/fossnewsbot)
