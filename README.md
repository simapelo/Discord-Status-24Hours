# Discord Status 24Hours
Discord Status [Streaming, Playing, Listening, Watching] Online 24/7

### Setting `Playing` status
await client.change_presence(activity=discord.Game(name="game name"))

### Setting `Streaming` status
await client.change_presence(activity=discord.Streaming(name="stream name", url=twitch_url))

### Setting `Listening` status
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.listening, name="music name"))

### Setting `Watching` status
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.watching, name="film name"))
