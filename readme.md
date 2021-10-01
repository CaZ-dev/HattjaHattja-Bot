
# HattjaHattja Discord JS Bot


## Version 2!
This updated version adds some new functionality to allow for the easy creation of more advanced
bots, and some updated help as well. The original simple-discord-js-bot code can be found [here on 
the v1.0 tag](https://github.com/CaZ-dev/HattjaHattja-Bot).

## Prerequisites
 * Node JS >= 12.0.0
 * NPM >= 6.9.0
 * Git

## Setup
1. Clone this repository: `git clone https://github.com/CaZ-dev/HattjaHattja-Bot` then navigate to the new 
   folder named `hattjaHattja-discord-js-bot`
2. Install dependencies with `npm i`
3. Edit `config.json`, replacing the placeholder values with your desired command prefix and your bot token (If you 
   don't have one yet, see the note below on how to generate one.)
4. Start the bot with `node index.js`
5. Add the bot to the server of your choice by filling out the details in this 
   [handy application](https://discordapi.com/permissions.html#7168) and clicking the generated link.

That's it! You can now try out the default commands like `!bot help`, or create your own and restart the bot to use them.

>**Note:**
If you don't already have a Discord bot application setup you can create one by going to the 
> [Discord Developer Portal](https://discord.com/developers/applications/me), then create a new application, give it a 
> name, go to the "Bot" tab, then click on "Add Bot", and you're good to go!


## Usage
After adding the bot to a server, call its command via `!bot commandname` where "!bot" is the prefix you defined in 
config.js and "commandname" is the name of a command defined and exported in the `commands` folder.

You can safely delete or modify the example commands `talk.js` and `weather.js` but it is recommended to keep `help.js`.

## Running the bot permanently
It's recommended that you use a process monitor like [PM2](https://pm2.keymetrics.io/) to run the bot instead of 
just `node`, that way it can be restarted on crashes and monitored.


