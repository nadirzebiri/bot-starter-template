# Discord Bot

This is a Discord bot that was created following the tutorial at https://discordjs.guide/. It is a basic bot that responds to some basic commands.

## Prerequisites

Before you get started, you will need to have the following tools installed on your machine:

- Node.js
- npm (comes with Node.js)

## Getting Started

To get started, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the root directory of the project and run `npm install` to install the dependencies.
3. Create a file called `.env` in the root directory of the project and add your Discord bot token, client ID, guild ID, and invite link like this:

```
TOKEN=your_bot_token_here
CLIENT_ID=your_bot_token_here
DEV_GUILD_ID=your_guild_id_here
INVITE_LINK=your_invite_link_here
```

Replace the placeholders with the actual values for your bot, which you can obtain from the [Discord Developer Portal](https://discord.com/developers/).

4. Run the bot with `npm start`.

## Scripts

Run the bot
`npm start`

Registering slash commands in the development guild
`npm dev-deploy`

Registering slash commands globally
`npm global-deploy`

## Commands

Here are the commands that the bot currently supports:

- `!ping`: The bot will respond with "Pong!".
- `!server`: The bot will provide information about the server.
- `!user`: The bot will provide information about the user.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
