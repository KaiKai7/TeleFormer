![teleformer logo](https://github.com/KaiKai7/TeleFormer/assets/87836320/ca6e59c7-1c9b-4f4d-8351-01124f45366d)

# TeleFormer User Guide

## About TeleFormer
TeleFormer is a utility to help simplify and automate the creating of web requests for Telegram. Sometimes things can get a little messy when formatting messages because special characters are sometimes needed to designate spaces and other functions. TeleFormer can automatically and quickly do this for you.
## About Telegram
Telegram is an open source and free messenger. You can use Telegram as a secure messenger or you can also use it for so much more. Such as iot projects with Raspberri Pie's and Arduino's. You can also make voice calls and video calls. Telegram is available on all major platforms and is free with a premium option. You can get Telegram here https://telegram.org

## Instructions For Use
There are 3 main things needed to create a text notification for Telegram.

### #1 Bot Token
The bot token is something that should be kept private, with it others could control your bot.

If you do not have Telegram installed yet, then you should install it before moving forward. Although it is not required, it will make the bot token and chat id process more automated.

There is a link to get the bot token and if you do not yet have one, then clicking the link will open Telegram and take you directly to the "BotFather". This is a bot that will help you create your bot.

* choose the option to create a new bot and follow the instructions.
* once the bot is created, you will be shown the bot token.
* copy this token and paste it in the field called "Bot Token".

### #2 Chat ID
The chat id identifies the chat to which you are sending the message. If you do not yet know what your chat id is, then you can use the link for the MyIdBot to tell you.

* once you have the chat id, paste it in the field called " Chat Id".

### #3 Message
The message field is where you type in the message you want to display. This field is pretty self explanatory but there are some features worth knowing.
* there is a limit to the number of characters that can be sent. Experiment with sending yourself some test messages to find out if the message you want to send will be truncated or not.
* Spaces are automatically encoded when the url is finally formatted. This saves you the trouble of knowing the special characters required to make spaces. It also makes composing a message easier.
* Multi-line messages are supported by Telegram. If the user presses the enter key while in the message field, the special characters for a new line are entered automatically. This needs to ne done so that the url will be valid and properly send. You will notice once the notification is received that the new lines started when the enter key was pressed. This is helpful for creating a notification with data in a more structured and visually appealing way.
* after typing in the text for the message decide whether you want to send the message as a silent notification or not. This is done by checking the checkbox if you want to send a silent message. Doing this encodes the message with an attribute to tell Telegram to deliver this message with no sound. This may be helpful if you are logging something and audible notfications are not only not wanted but not allowed.
* after typing in the message and choosing whether to send silent or not, press Format Url.
* the url is now displayed and can also be copied by pressing the url for at least one second. Depending upon your version of Android, this may also bring up the share menu.
* sharing to your browser of choice will immediately send the message as a http request. And when the browser refreshes you should see a message indicating whether successful or not.




