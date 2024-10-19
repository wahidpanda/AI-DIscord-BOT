# AI-DIscord-BOT
A Discord bot that utilizes LLM for responding to user messages in a specific channel.


# Discord AI Bot

A Discord bot that utilizes Google Generative AI for responding to user messages in a specific channel.

## Features
- Uses Google Generative AI to generate responses.
- Responds to user messages in a designated channel.
- Written in JavaScript with `discord.js` and `@google/generative-ai`.

## Prerequisites
- Node.js (version 16.6.0 or higher)
- A Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications).
- A Google Generative AI API key from [Google Cloud](https://cloud.google.com/).

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-ai-bot.git
   cd discord-ai-bot

2. Install dependencies:

   npm install discord.js @google/generative-ai


3. Create a .env file with the following content:

   API_KEY=your-google-generative-ai-api-key
  BOT_TOKEN=your-discord-bot-token
  CHANNEL_ID=your-target-channel-id

4. Start the bot:
   node index.js


**Usage**

The bot listens to messages in the specified channel and replies using Google Generative AI.
To change the channel, update the CHANNEL_ID value in the .env file.
Contributing
Feel free to open issues or submit pull requests with any improvements or bug fixes.

**License**

This project is licensed under the MIT License.


### `package.json`
```json
  {
    "name": "discord-ai-bot",
    "version": "1.0.0",
    "description": "A Discord bot that uses Google Generative AI for responses.",
    "main": "index.js",
    "scripts": {
      "start": "node index.js"
    },
    "dependencies": {
      "discord.js": "^14.0.0",
      "@google/generative-ai": "^1.0.0"
    },
    "author": "Your Name",
    "license": "MIT"
  }
```
index.js
This is the code you provided earlier, saved as index.js.

Now, you can create a GitHub repository with the above structure. Here’s how:

1. Go to GitHub and create a new repository named discord-ai-bot.
2. Clone the repository to your local machine using git clone.
3. Add the files (.gitignore, README.md, index.js, package.json).
4 Commit the changes:
  git add .
git commit -m "Initial commit with Discord AI bot code"
5. Push to GitHub:
   git push origin main


This will set up your GitHub repository and have all the necessary documentation for others to understand and use your bot. Happy Coding !



