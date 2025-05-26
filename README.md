# Reddit Notifier Chrome Extension

A Chrome extension that monitors specified subreddits for new posts and sends notifications to Discord using webhooks.

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

## Configuration

### Basic Setup
1. Click the extension icon in the Chrome toolbar to open the popup
2. Enter the subreddit you want to monitor (without the "r/")
3. Enter your Discord webhook URL (create one in your Discord server settings)
4. Set the refresh interval in minutes (minimum 5 minutes for free version)
5. Toggle the "Enable Monitoring" switch to start monitoring
6. Click "Save Settings" to apply your changes

## Usage

- The extension will automatically check for new posts at the interval you specified
- If you already have the subreddit open in a tab, the extension will refresh that tab
- If no tab is open with the subreddit, a new background tab will be created
- You can click "Check Now" to immediately check for new posts
- When new posts are found, they will be sent to your Discord channel via the webhook
- The extension keeps track of posts it has seen to avoid duplicate notifications
- You can disable monitoring at any time by toggling the switch and saving
