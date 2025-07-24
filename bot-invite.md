# Discord Bot Invite Instructions

## Bot Information
- **Bot Name:** lofi#5394
- **Application ID:** 1373570841559957504

## Invite URL with Required Permissions
Use this URL to invite the bot to your Discord server with all necessary permissions:

```
https://discord.com/api/oauth2/authorize?client_id=1373570841559957504&permissions=3148800&scope=bot%20applications.commands
```

## Required Permissions
- **Connect** - Join voice channels
- **Speak** - Play audio in voice channels  
- **Use Slash Commands** - Enable /join, /leave, /pause, /resume, /status commands
- **Send Messages** - Respond to commands
- **View Channels** - See channel list

## How to Fix "Unknown Integration" Error
1. Remove the bot from your Discord server (if already added)
2. Use the invite URL above to re-add the bot with proper permissions
3. Wait 1-2 minutes for Discord to sync the slash commands
4. Try using `/status` command in any text channel

## Available Slash Commands
- `/join` - Join voice channel and start playing lofi music
- `/leave` - Leave the voice channel  
- `/pause` - Pause the music
- `/resume` - Resume the music
- `/status` - Show current bot status

The bot will automatically find and join the first available voice channel when using `/join`.