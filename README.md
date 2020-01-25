# CorrectorBOT
A simple Discord bot to "correct" links with more private versions. Currently strips UTM parameters from Reddit links, redirects YouTube.com to Invidio.us and redirects Twitter.com to Nitter.net.

# Instructions

Run the bot with `python3 bot.py`.

Once you do that, the bot will create its own config folder.

The bot, however, cannot create its own `config.json` file.

Make a config.json file in the bot's config folder (shown in the output) with this template:
```
{
    "token": "bot account token here"
}
```
Run the bot again.
