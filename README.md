# Owl Music

## Installation guide:  
#### - Navigate to `https://discord.com/developers/applications`
#### - Click on New Application and name it  
#### - Enter your application page and navigate to Bot  
#### - Create a new bot and copy it's Token  
#### - Create a `.env` file and paste the token there like so: ```TOKEN=MYTOKEN```
#### -Navigate to OAuth2 -> URL Generator -> Mark the following items:  
- applications.commands
- bot
- administrator
#### - Enter the given url and add the bot into your server
#### - Navigate to General Information -> Copy your bot's Application ID
#### - Paste it under `CLIENT_ID` in the `.env` file
#### - Copy your discord server ID and paste it under `GUILD_ID` in the `.env` file
#### - Use `node index.js load` to load the bot  
#### - Use `node index.js` to start the bot
