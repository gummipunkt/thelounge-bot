# mailcow-bot

A node-js IRC bot for [mailcow](https://mailcow.email) IRC channel on freenode.


### Setup and running
```sh
$ yarn
$ yarn test
$ yarn start
```

### Config
Configuration information can be found in the config.json. The default options are below
```js
var config = {
	channels: ["#mailcow"],
	server: "chat.freenode.net",
	botName: "Brunhilde",
	realName: "Mailcow IRC Bot",
	commandPrefix: "!",
	ignore: ["Brunhilde"],
	githubUser: "mailcow",
	githubRepo: "mailcow-dockerized",
	owners: ["gummipunkt", "andryyy"]
}
```
