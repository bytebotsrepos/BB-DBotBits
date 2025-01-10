PLEASE NOTE WE NO LONGER UPDATE THIS PACKAGE, Please download NPM version
![bb](https://github.com/user-attachments/assets/8cf39b43-3d48-4436-a468-b45a0b7bca66)

PLEASE NOTE: this is early beta

bytebots.net 

BB-DBotBits Library

Your fastest route to creating Discord bots with minimal effort. Our library is designed to cater to developers at all skill levels, from beginners building their first bot to experienced users seeking to streamline their development process.

About:
The ByteBots Library simplifies the process of Discord bot development by offering pre-built functions and modules, making it easy to create bots that range from basic to advanced. Our tools are designed to help you get up and running quickly, focusing on your bot's unique features instead of spending time on repetitive setups.

Features:
- Simple and Intuitive: Built with ease of use in mind. No complex configurations.
- Fast Development: Focus on your bot's features, not the boilerplate. Get up and running quickly.

NOTE:
You will need to make a token.env file inside the token.env you need to add this:
token=yourToken
Replace your token with your token.

And edit settings inside settings folder.

Documentation:
For detailed documentation, setup instructions, usage examples, and troubleshooting tips, visit our website: bytebots.net

Note: Depending on the number of building blocks in your bot, it may take up to 5 minutes to register all commands. If commands do not appear after a few minutes, simply restart Discord.

If you encounter any issues, feel free to reach out via our Discord server: https://discord.gg/pqbUrYN9h4

Current Limitations:
/purgemessages is currently limited to a maximum of 100 messages.

Available Modules:
Here are the pre-built modules included in the ByteBots Library:

const { discordReply } = require('./BB-DBotBits/discordReplies.js'); // Import Replies
const { discordTickets } = require('./BB-DBotBits/discordTickets.js'); // Import discordTickets
const { discordReverse } = require('./BB-DBotBits/discordReverse.js'); // Import discordReverse
const { discordRadio } = require('./BB-DBotBits/discordRadio.js'); // Import discordRadio
const { discordLogin } = require('./BB-DBotBits/discordHandler.js'); // Import discordLogin
const { checkSpamRate } = require('./BB-DBotBits/checkSpamRate'); // Import checkSpamRate
const { discordPurgeCommands } = require('./BB-DBotBits/discordPurge'); // Import purge command setup
const { settings: discordRules } = require('./BB-DBotBits/discordRules'); // Import Rules
const { discordReplyEmbed } = require('./BB-DBotBits/discordReplyEmbed.js'); // Import the embed function
const { discordXP } = require('./BB-DBotBits/discordXP.js'); // Embed
const token = require('./token'); // Import your bot token

Example Function Calls:
Here are some examples of how to use the ByteBots Library:

Simple Reply:
discordReply('helloworld', 'Ohhh, so it starts!');

Play a Radio Stream:
discordRadio('RadioName', 'https://streamurl.com', 'https://imageurl.com');

// Call XP

discordXP();

Embed a Message:
discordReplyEmbed(
    'announcenew', // Command trigger
    'Important Update', // Embed title
    'We have some exciting new features coming soon! Stay tuned.', // Embed description
    'This is a footer text', // Footer text
    'https://example.com/update-image.png', // Optional image URL
    'https://example.com/more-info' // Optional clickable URL
);

Purge Commands:
discordPurgeCommands();

Open a Ticket:
discordTickets();

Check Spam Rate:
checkSpamRate();

Support:
Need help? Join our Discord server: https://discord.gg/pqbUrYN9h4 for assistance and to connect with other developers.

If you find this library helpful, please consider buying me a coffee – your support is greatly appreciated:
https://buymeacoffee.com/coffeeismyonlyfriend
