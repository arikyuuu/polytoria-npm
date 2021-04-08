# polytoria-npm
## Installation
`$ npm install polytoria-js`

## Usage
+ Users
    * GetById
    * GetByName
+ Guilds
    * GetById
+ Items
    * GetById
    * GetByInstanceId
+ Games
    * GetById


## Example
Getting player's id from username
```js
const p = require("polytoria-js")
p.users.getByName("Polytoria").then(function (res) {
	console.log("Polytoria's ID is "+ res.id);
}).catch(function (e) {
	console.error(e);
});
```

## Changelog
* 0.0.1 - Initial release
