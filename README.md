# Celestia Discord Bot
A Discord Bot with focus on Fun, Moderation, Economy and Utility commands.

This Discord Bot has over 120 commands, from Fun to Moderation, from Anime to Utility. 

YOU ARE FREE TO USE ITS CODE AS REFERENCE FOR YOUR OWN BOTS. 

## Filling out the .env file

*Note: Please remove the .example part of it, once you are done.*

### Bot-related Information:
* `CELESTIA_TOKEN=` is the bot's token. You can get it from https://discord.com/developers/applications/
* `CELESTIA_PREFIX=` is the default prefix of the bot. Can be changed to anything you want. Default is c.
* `ADMIN=` Bot Admin User ID. Not required, and totally optional.
* `SUPPORT=` Bot Support User ID. Not required, and totally optional.
* `SYSTEMNOTICE=` Please leave it this to `true`, which is set by default. This shouldn't be touched.

### Roles:

*Note:  Feel free to change these roles for your server. It's not required to change them though. Defaults below. Those are for the permission level function, so that the bot knows who is an Admin, Moderator, or user.*
* `MODROLE=` Moderator role on a server. Default is `Moderator`.
* `ADMINROLE=` Admin role on a server. Default is `Admin`.

### API KEYS, Secrets, and more:

* `GOOGLE_API=` You can get the Google API Key by creating a new Application on the [Google Cloud Console.](https://console.cloud.google.com/home/dashboard). After that, you need to enable the [YouTube Data API](https://console.cloud.google.com/marketplace/product/google/youtube.googleapis.com?q=youtube&id=125bab65-cfb6-4f25-9826-4dcc309bc508&project=azura-278914&hl).
* `GIPHY_API_KEY=` You can get the Giphy API Key by visiting the [Giphy API Page](https://developers.giphy.com/).

# Feedback Command
*Note: This is a Channel ID for the channel you want to view feedback from. It's not really required, so delete it, with the feedback command, if you don't want or need it.*
`FEEDBACKCHANNEL=` is simply the channel ID of any channel in the main server the bot should be in.

