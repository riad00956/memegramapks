# Memegram

A Telegram-style bot-only chat application built with React, TypeScript, and Tailwind CSS.

## Features
- **Splash & Login**: Premium splash screen and bot token login.
- **Bot-Only**: Interacts with users who send `/start` to your Telegram bot.
- **Telegram UI**: Premium Telegram-style chat list and chat screen.
- **Local Storage**: All messages and metadata are stored locally on the device (using `localStorage` for web, would be `AsyncStorage` or `SQLite` for native).
- **Auto-Cleanup**: Automatically clears messages and media older than 24 hours.
- **Dark/Light Mode**: Full theme support with smooth transitions.
- **Offline-Friendly**: View your chats and messages even without an internet connection (once loaded).

## Setup
1. Get a Bot Token from [@BotFather](https://t.me/BotFather).
2. Start the app and enter your token.
3. Send `/start` to your bot from any Telegram account.
4. Your chat will appear in the app!

## GitHub Actions
The project includes a `.github/workflows/build.yml` file for automatic APK/IPA builds via Expo EAS.

## Footer
powered by ꪑꫀꪑꫀ ꪜꪖ꠸ꪗꪖ
