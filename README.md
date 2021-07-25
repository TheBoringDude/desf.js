<div align="center">
    <h1>desf</h1>
    <p>A simple Express-Like DiscordJS framework. </p>
</div>

This is just a small wrapper to the DiscordJS library with the help of the guide from https://discordjs.guide.

## Usage

```js
import Desf from "desf";

// create a new instance
const bot = new Desf(process.env.token, { prefix: "!" });

bot.command("hello", (message, args) => {
  message.send("Hello! This is Desf!");
});

bot.run();
```

##

#### &copy; 2021 | [MIT](./LICENSE)