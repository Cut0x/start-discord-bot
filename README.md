# Make a Discord bot simply !
This template allows you to start your bot with a complete infrastructure !

# Tutorial
***More up to date video with the new code!***<br>
[![Bannière](http://img.youtube.com/vi/LLTMeutpcyw/0.jpg)](https://www.youtube.com/watch?v=LLTMeutpcyw "FR - Faire un bot #discord (v14) 🖥️")

# Ressources
<a href="https://www.npmjs.com/package/simple-djs-handler">simple-djs-handler</a>, <a href="https://www.npmjs.com/package/discord.js">discord.js</a>, <a href="https://www.npmjs.com/package/path">path</a>, <a href="#">fs</a>

# Install modules
```
npm install
```

# Where to configure the bot?
You have to go to the redirect `./data/config.js` (<a href="https://github.com/Cut0x/start-discord-bot/blob/main/data/config.js">Click here !</a>) to edit the build file as below:
```js
module.exports = {
    bot: {
        token: "token_of_your_app",
        client_id: "id_of_your_app",
        owner_bot: "your_discord_id",
        maintenance: false // put true if you want only you can do the orders
    }
};
```

# Are you having a problem ? the code does not work ?
Contact me by my private messages <a href="https://twitter.com/cut0x_">Twitter</a> or <a href="https://instagram.com/valloic_">Instagram</a> with all the information (the complete error in READABLE image).
You can also contact me through the <a href="https://github.com/Cut0x/start-discord-bot/discussions/1">message category</a> of the project !
