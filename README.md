# Api Documentation

Main API Endpoint
https://discordboats.xyz/api

## POST /bot/:id

Post your bot server count.
Authorization header required with your bot's API token. 
Example:
```javascript
Authorization: TOKEN 
content-type: application/json 
{"server_count": 10}
```

Token can be found at the api section of https://discordboats.xyz


## GET /bot/:id

Get bot information from the api.
Example response:
```javascript
        {  
            "id":"365958655926992896",
            "name":"Luki",
            "prefix":"l.",
            "lib":"discord.js",
            "server_count":2221,
            "shortDesc":"Luki is an easy-to-use bot with commands that can be used for fun, moderation, games, and more!",
            "desc":"I am VERY!!! kewl bot",
            "avatar":"cd50f6c11a30a4e9f76f825d8c4512a9",
            "ownerid":"231733082804322304",
            "ownername":"MrSheldon#0001",
            "invite":"https://discordapp.com/oauth2/authorize?client_id=365958655926992896&scope=bot&permissions=2146958591",
            "discord":"https://discord.gg/76PAmCv",
            "website":"https://luki.xyz",
            "inQueue":"no",
            "certified":"yes",
            "vanity_url":"luki"
        }
```
## GET /user/:id

Get user information from the api.
Example response:
```javascript
        {  
            "id":"231733082804322304",
            "name":"MrSheldon",
            "website":"https://mrsheldon.me",
            "twitter":"realMrSheldon",
            "github":"MrSheldon",
            "instagram":null,
            "reddit":null,
            "bio":"Discord fanatic and #HouseOfBrilliance HS | Founder and Lead Developer of Luki The Bot"
        }
```

## Official packages

* [Boats.js](https://boats.js.org/)
* [Boats4J](https://github.com/DiscordBoats/Boats4J)


## Community packages

* [discordboats.xyz](https://www.npmjs.com/package/discordboats.xyz) by [@DetectiveHuman](https://github.com/DetectiveHuman) 
