
# Discord Server Logger Bot
<p align="left">
<a href="https://github.com/sponsors/DEEM-0001" target"_blank"> <img src="https://img.shields.io/github/sponsors/DEEM-0001?label=Sponsors&logo=GitHub%20Sponsors&style=for-the-badge" /> </a>
<a href="https://discord.gg/UdKSrxBXyd" target"_blank"> <img src="https://img.shields.io/discord/993525327798210681?label=Support&logo=DISCORD&style=for-the-badge" /> </a>
<a href="https://github.com/DEEM-0001/Logger-Bot" target"_blank"> <img src="https://img.shields.io/github/contributors/DEEM-0001/Logger-Bot?color=dark-green&logo=GITHUB&style=for-the-badge" /> </a>

Discord bot that logs all changes on your Discord server! When using this code please give credits to **DEEM#6666**!

## Deployment

Follow these instructions on how to use the bot.

    1.  Press the green "Code" button at the top of the repo.
![template](https://cdn.discordapp.com/attachments/1008855081489268857/1008856275100106752/HNp.png)

    2.  Download the full code via the "Download ZIP" button
![downloadcode](https://cdn.discordapp.com/attachments/1008855081489268857/1008856994838491177/hdg.png)

    3. Extract the files to your desktop and open the files in Visual Studio Code (or other text editor)

**.env**
```bash
TOKEN=YOUR_BOT_TOKEN
```
**config.json**
```bash
{
    "guildID": "1050735132182581288",
    "channels": {
        "channellog": "1069250417105567824",
        "emojilog": "1069255441063891044",
        "banlog": "1009561547468701756",
        "unbanlog": "1009842927561871372",
        "joinlog": "1009844170942324926",
        "leavelog": "1010592671200464976",
    },
    "owner": "975898528859697182",
    "version": "1.4.0" // Dont change this!
}
```
    4. Change things in the .env and src/utils/config.json files, then open a terminal and run the following commands

Downloading discord.js
```bash
npm i discord.js@latest
```

Download the necessary modules:
```bash
npm i
```

Then use this command to turn on the bot:
```bash
node .
```

## Packages that this bot uses
- [colors](https://www.npmjs.com/package/colors) Copyright (c) Marak, used under license [MIT](https://github.com/Marak/colors.js/blob/master/LICENSE).
- [dotenv](https://www.npmjs.com/package/dotenv) Copyright (c) motdotla, used under license [BSD 2-Clause](https://github.com/motdotla/dotenv/blob/master/LICENSE).
- [figlet](https://www.npmjs.com/package/figlet) Copyright (c) patorjk, used under license [MIT](https://github.com/patorjk/figlet.js/blob/master/LICENSE.txt).
- [moment](https://www.npmjs.com/package/moment) Copyright (c) Moment.js, used under license [MIT](https://github.com/moment/moment/blob/develop/LICENSE).

## CHANGELOG
- 16.08.22 - Fixed broken presence and finished **channelUpdate** log
- 17.08.22 - Code has been improved, logger has been added to event folder and emoji logger has been added
- 18.08.22 - Added ban and join log
- 29.01.23 - Modified code to discord.js **version 14.7.1**

## Message from the creator
If I see you using this code as your own, I will report the license violation to GitHub
