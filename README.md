# telegrambot_haramemam

In order to make it easier for users to navigate the bot multiverse, we ask all developers to support a few basic commands. Telegram apps will have interface shortcuts for these commands.
●	/start - begins interaction with the user, e.g., by sending a greeting message. This command can also be used to pass additional parameters to the bot (see Deep linking)
●	/help - returns a help message. It can be a short text about what your bot can do and a list of commands.
●	/settings - (if applicable) returns the bot's settings for this user and suggests commands to edit these settings.
Users will see a Start button when they first open a conversation with your bot. Help and Settings links will be available in the menu on the bot's profile page.
Use the /newbot command to create a new bot. The BotFather will ask you for a name and username, then generate an authentication token for your new bot.
The name of your bot is displayed in contact details and elsewhere.
The Username is a short name, to be used in mentions and t.me links. Usernames are 5-32 characters long and are case insensitive, but may only include Latin characters, numbers, and underscores. Your bot's username must end in 'bot', e.g. 'tetris_bot' or 'TetrisBot'.
The token is a string along the lines of 110201543:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw that is required to authorize the bot and send requests to the Bot API. Keep your token secure and store it safely, it can be used by anyone to control your bot.
