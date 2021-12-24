# discord-status-24hours
Discord Status [Streaming, Playing, Listening, Watching] Online 24/7

# Setting `Playing` status
await client.change_presence(activity=discord.Game(name="nama game"))

# Setting `Streaming` status
await client.change_presence(activity=discord.Streaming(name="nama stream", url=twitch_url))

# Setting `Listening` status
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.listening, name="nama lagu"))

# Setting `Watching` status
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.watching, name="nama film"))
