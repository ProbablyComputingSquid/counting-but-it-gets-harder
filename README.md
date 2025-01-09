# counting but it gets harder and harder

<a href="https://discord.com/oauth2/authorize?&client_id=1326208864814633093&scope=bot+applications.commands&permissions=8"><button>Invite me to your server</button></a>

this was a discord bot inspired by the popular "counting" where people count numbers solely for the sake of "number go up"

One of my friends said, "hey what if it was counting but every time someone failed to count correctly, their channel slowmode would increase?"<br>
So then, I set out to do this. <br>

### Running it yourself?
- Grab your bot token from the discord bot portal, and place it in .env.example, and rename it to .env
- make sure to install all dependencies
- on the discord bot page, select "read messages" in the intents section
- git clone the repository and run `python3 bot.py` as the bot should create all data storage files needed while running
- you're set to go now!
<h2>📂 Project Contents: </h2>

```
/data
    _servers.json - mapping of server data
    {server_id}.json - seperate json file for each server "guild's" data
    ...
.env - where your bot token should go
.gitignore
boy.py - actual bot code
example.json - what a {server_id}.json should look like
LICENSE 
README.md
```

# If you're from hack club
Please consider voting!