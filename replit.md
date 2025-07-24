# Discord Lofi Bot

## Overview
A Discord bot that streams lofi music from YouTube 24/7 in voice channels. Built with Discord.js, Express backend, and React frontend for bot management.

## Project Architecture
- **Frontend**: React with Vite, TypeScript, shadcn/ui components
- **Backend**: Express.js server with TypeScript
- **Database**: PostgreSQL with Drizzle ORM
- **Bot**: Discord.js for voice channel integration
- **Music**: play-dl library for YouTube streaming

## Recent Changes
- ✅ Successfully connected Discord bot as "lofi#5394" with valid token
- ✅ Fixed all TypeScript compilation errors in music.ts and index.ts
- 🔄 **MIGRATING TO PLAY-DL**: Switching from ytdl-core to play-dl for better YouTube reliability
- ✅ Configured dotenv for proper environment variable loading
- ✅ Fixed database schema compatibility issues and removed unsupported fields
- ✅ **EXPANDED SLASH COMMANDS**: Successfully implemented 12 slash commands
- 🔄 **FIXING YOUTUBE FUNCTIONALITY**: Implementing proper YouTube URL playback and search
- ❌ **REMOVED LOFI AMBIENT**: Completely removed background lofi music generation
- ✅ **WEB INTERFACE YOUTUBE**: Added dedicated YouTube input form in web interface
- 🔄 **AUDIO STREAMING**: Bot now only plays music from YouTube sources

## Current Status
- ✅ **Discord Bot Online**: Successfully connected as "lofi#5394"
- ✅ **Voice Channel**: Bot successfully joins voice channels on command
- 🔄 **YouTube Music**: Implementing play-dl for proper YouTube music streaming
- ❌ **Lofi Ambient Music**: REMOVED - no more background ambient music
- ✅ **Web Interface**: Fully functional for bot control with YouTube input form
- ✅ **Discord Slash Commands**: All 12 commands working (/join, /leave, /pause, /resume, /status, /play, /skip, /stop, /queue, /volume, /nowplaying, /loop)
- ⚠️ **Database**: PostgreSQL connection failing, using memory storage fallback

## Technical Solution
- **Music Source**: Generated ambient tones instead of YouTube (avoiding 410 errors)
- **Audio Generation**: Continuous lofi-style chord progressions using sine waves
- **Voice Detection**: Automatically finds first available voice channel if none specified
- **24/7 Operation**: Continuous audio stream without interruption

## User Preferences
- Language: Indonesian (user communicates in Indonesian)
- Bot should stream lofi music continuously (24/7)
- Web interface for bot management and control

## Completed Tasks
✅ Bot connects to Discord successfully
✅ Bot joins voice channels and plays music  
✅ Web interface controls work (join/pause/resume/leave)
✅ 24/7 continuous audio streaming implemented
✅ Resolved YouTube 410 errors with alternative approach
✅ Added Discord slash commands - expanded from 5 to 12 commands
✅ Fixed "application did not respond" error with proper command registration
✅ Fixed audio encoding with opusscript - users can now hear the bot
✅ Added proper slash command debugging and error handling
✅ Created bot invite URL with correct permissions (see bot-invite.md)
✅ Implemented YouTube URL playback functionality
✅ Added music search capability (with lofi fallback)
✅ Enhanced music system with proper track information storage