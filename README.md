```js
const { LumexScript } = require("@pealse-studio/lumex-script");

const bot = new LumexScript({
    commands: "commands",
    prefixes: [ "!", "." ]
});

bot.connect("token");
```
