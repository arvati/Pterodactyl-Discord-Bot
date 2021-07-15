# Pterodactyl-Discord-Bot

This is a fork from https://github.com/Linux123123/Pterodactyl-Discord-Bot
Thanks Linux123123 for his great job

[![GitHub](https://img.shields.io/github/license/arvati/Pterodactyl-Discord-Bot)](https://github.com/arvati/Pterodactyl-Discord-Bot/blob/main/LICENSE)
[![GitHub package.json dependency version (prod)](https://img.shields.io/github/package-json/dependency-version/arvati/Pterodactyl-Discord-Bot/@linux123123/jspteroapi)](https://www.npmjs.com/package/@linux123123/jspteroapi)
[![GitHub issues](https://img.shields.io/github/issues/arvati/Pterodactyl-Discord-Bot)](https://github.com/arvati/Pterodactyl-Discord-Bot/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/arvati/Pterodactyl-Discord-Bot)](https://github.com/arvati/Pterodactyl-Discord-Bot/pulls)

<h3>A simple pterodactyl discord bot using Linux123123 API library, that has a own permission system.</h3>

# Pterodactyl panel

You can run the bot in the panel. You just need to import the [egg provided](https://github.com/arvati/Pterodactyl-Discord-Bot/raw/master/egg-discord-pterodactyl-bot.json) and create a server with it.    
You may allocate 127.0.0.1:10080 port to it, no need of external ingress open port.    

# Manual installation

<h5>Requirements</h5>

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**<br>
2. Add the bot to your discord server [see this page, but change the client ID with your APPLICATION ID](https://discordapi.com/permissions.html#3021040720)
3. Node.js v14.0.0 or newer

<h5>Install from the command line:</h5>

```bash
git clone https://github.com/arvati/Pterodactyl-Discord-Bot.git
yarn install --production
yarn build
yarn start
```

# Permissions

There are 10 permission levels. They are defined in `config.js`

| Level name    | Corresponding role   | Level | Guild role     |
| ------------- | -------------------- | ----- | -------------- |
| User          | everyone (default)   | 0     | :green_circle: |
|               |                      | 1     |                |
| Moderator     | Server moderator     | 2     | :green_circle: |
| Administrator | Server administrator | 3     | :green_circle: |
| Server Owner  | Server owner         | 4     | :green_circle: |
|               |                      | 5     |                |
|               |                      | 6     |                |
|               |                      | 7     |                |
|               |                      | 8     |                |
|               |                      | 9     |                |
| Bot Creator   | Linux123123          | 10    | :red_circle:   |

The rows without any information are left to change if you want to add more roles.

# Disclaimer

I am not responsible for any damages that you cause to your servers/nodes by using this bot.

Remember: This bot can potentially be dangerous with the ability to Delete Servers/Nodes at an instant!

# Contributors

Created and maintained by [Linux123123](https://github.com/linux123123).   
This is a fork from it.
