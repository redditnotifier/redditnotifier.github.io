# Reddit Notifier Chrome Extension

A Chrome extension that monitors specified subreddits for new posts and sends notifications to Discord using webhooks.

## Features

### Basic Features (Free Version)
- Monitor a single subreddit for new posts
- Set custom refresh intervals (minimum 5 minutes)
- Send notifications to Discord via webhook
- Track seen posts to avoid duplicate notifications

### Premium Features
- Monitor up to 10 subreddits simultaneously
- Faster refresh rates (down to 1 minute)
- Custom notification templates (coming soon)
- Multiple Discord webhooks  (coming soon)
- Advanced filtering options (coming soon)

## UI Layout

The extension has a user-friendly interface with three main pages:

1. **Basic**: Contains settings for the free version
2. **Premium**: Contains advanced settings for premium users
3. **License**: Allows users to activate or purchase a premium license

### Global Elements
- **Settings Button**: Located in the top-right corner, providing access to reset functions
- **Status Indicators**: Shows current monitoring status, last check time, and next check countdown

## License

This extension is available in both free and premium versions. The premium version can be activated with a license key.

## Development

To run this extension locally:
1. Clone this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the extension directory

## Installation

1. Clone or download this repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" (toggle in the top-right corner)
4. Click "Load unpacked" and select the folder containing the extension files
5. The extension icon should appear in your Chrome toolbar

## Configuration

### Basic Setup
1. Click the extension icon in the Chrome toolbar to open the popup
2. Enter the subreddit you want to monitor (without the "r/")
3. Enter your Discord webhook URL (create one in your Discord server settings)
4. Set the refresh interval in minutes (minimum 5 minutes for free version)
5. Toggle the "Enable Monitoring" switch to start monitoring
6. Click "Save Settings" to apply your changes

### Premium Features
1. Navigate to the "License" tab and enter your premium license key
2. After activation, you'll have access to the Premium tab
3. Add multiple subreddits to monitor (up to 10)
4. Create custom notification templates
5. Configure individual settings for each subreddit

## Usage

- The extension will automatically check for new posts at the interval you specified
- If you already have the subreddit open in a tab, the extension will refresh that tab
- If no tab is open with the subreddit, a new background tab will be created
- You can click "Check Now" to immediately check for new posts
- When new posts are found, they will be sent to your Discord channel via the webhook
- The extension keeps track of posts it has seen to avoid duplicate notifications
- You can disable monitoring at any time by toggling the switch and saving

## Monetization

The extension uses a freemium model with:
- Free tier: Basic functionality with limited features
- Premium tier: Full access to all features with a paid license key

Premium licenses are available as:
- Monthly subscription
- Annual subscription (20% discount)
- Lifetime purchase

## Notes

- For best performance, don't set the refresh interval too low
- Discord webhook URLs should be kept private to prevent misuse
- Premium licenses are tied to your Chrome account and can be used on multiple devices

## Icon Credits

The placeholder icons in this extension need to be replaced with actual PNG files before publishing. 