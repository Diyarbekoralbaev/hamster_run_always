# Hamster Kombat Bot

## Introduction

Welcome to Hamster Kombat! This guide will help you run the game in your browser and integrate it with Telegram.

## Prerequisites

1. A modern web browser (Chrome, Firefox, etc.).
2. Telegram account and access to the Telegram Web App.

## Installation

### Step 1: Set Up Browser Extension

To run Hamster Kombat in your browser, follow these steps:

1. Install the browser extension [Resource Override](https://chromewebstore.google.com/detail/resource-override/pkoacgokdfckfpndoffpifphamojphii).
2. Open the extension settings and configure it with the following data:
   - **Tab URL:** `*`
   - **From:** `https://hamsterkombat.io/js/telegram-web-app.js`
   - **To:** `https://evgeniyvorobev.github.io/hamster-kombat-bot/telegram-web-app.js`

### Step 2: Launch the Game

1. Open the [Hamster Kombat Bot](https://web.telegram.org/) on Web telegram.

## Sending Bearer Token to the Bot

To authenticate and interact with the bot, follow these steps:

1. Open the Chrome Developer Tools (F12 or right-click and select "Inspect").
2. Go to the "Network" tab.
3. Start the game in your browser.
4. Find the `me-telegram` request in the network activity.
5. Copy the Bearer token from this request. (in header)
6. Send the Bearer token to the bot.

## Notes

- Ensure you have a stable internet connection while playing the game.
- If you encounter any issues, refer to the extension's troubleshooting guide or contact support.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all contributors and users for their support.
- Special mention to the developers of the Resource Override extension.

Happy hacking!

## See tutorial on YouTube:
How to use: [Youtube Tutorial](https://youtu.be/4irin0Fo7LA)
