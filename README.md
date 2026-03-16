<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/JtC8H4J2/Rounded-Rectangle.png' border='0' alt='Rounded-Rectangle' height='25'></a>
# 📜 | SER Discord

SER Discord is a complete SCPSL + Discord script package that includes things such as a:

- Server List
- Basic Loging System
- Report Loging System
- Event Loging System(Command Ran)


## ⚙️ | How To Set Up -- Required Settings

**ALL** of these steps require the ***`SERDiscordConfig.txt`*** file.

![](https://i.postimg.cc/KjnjFjpL/image-2026-02-22-200833959.png)

### Server logs
1. Set your server name.
    - Change the value of the `$serverName` variable to be your server name.
    E.g. `$serverName = "My Cool Server"`. If this variable is not changed, the package will **not** error, but will throw a **warning**.

2. Create a webhook in your SCP:SL Server logs channel(create an sl logs channel if you don't have one) and copy the link.
    - This webhook can be named **anything** as the webhook will always use the value in `$serverName` when sending a message.

3. Once you have the webhook set up, change the value of the `$serverLogsWebhook` variable to be the webhook link.

> Advanced logs are still being worked on and will have a true/false setting to enable and disable them.

### Server List
> Create a server list channel if you haven't already

1. Set your server name.
    - Change the value of the `$serverName` variable to be your server name.
    E.g. `$serverName = "My Cool Server"`. If this variable is not changed, the package will **not** error, but will throw a **warning**.

2. Create a webhook in your **server list** channel and copy the link.

3. Once you have the webhook set up, change the value of the `$serverListWebhook` variable to be the webhook link.

4. Run the `SendServerList` command in your server console and copy the message ID displayed.

5. Change `$serverMessageId` to the message ID you coppied in [4]

6. Restart the round.

## ⚙️ | Customization

> SOON
