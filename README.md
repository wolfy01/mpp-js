# MPP.JS
### Example Usage:
```js
import Client from "@wolfy01/mpp-js";

const client = new Client({
    token: "<YOUR_BOT_TOKEN>"
});

client.setChannel(decodeURI("β§πππ₯%20π‘πΈπΈπΆβ§"));
client.start();

client.on("hi", msg => {
    console.log(msg);
});

client.on("a", msg => {
    console.log(msg);
});
```

# Contributing is welcome!
### Please make a pull request to contribute to this project.
### If anyone is willing to work on the documentation for this, it would be greatly appreciated.