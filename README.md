# Reward Tracker

Tracks your Roblox mission rewards in the background and posts them to Discord.

## Download

**[Download RewardTracker.exe](https://github.com/Shrektella/RewardTracker-data/releases/latest)** - put it anywhere and run it. That's the whole install.

1. Run `RewardTracker.exe`. The window opens once (after that it lives in the tray, by the clock).
2. In **Settings**, paste a Discord webhook URL
   (your Discord channel → Edit Channel → Integrations → Webhooks → New Webhook → Copy Webhook URL).
3. On **Rewards**, switch on **Track** for the rewards you care about.

It only looks at the screen - it never clicks, types or takes focus from the game.
The reward list updates by itself. When a new version comes out, the app tells you and links here.

## What's in this repo

- `catalog/icons/` - the shared reward list. Each picture is one reward; the file name is its name.
- `catalog/settings.json` - settings every app uses (e.g. where new rewards are sent for naming).
- `latest.json` - the newest version number, so apps can say when an update is out.
