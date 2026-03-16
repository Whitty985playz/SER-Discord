<a href='https://discord.com/invite/27A97rxR' target='_blank'><img src='https://i.postimg.cc/JtC8H4J2/Rounded-Rectangle.png' border='0' alt='Rounded-Rectangle' height='25'></a>
# 📜 | SER Discord

SER Discord is a complete SCP:SL + Discord script package that includes things such as a:

- Server List
- Basic Loging System
- Report Loging System -- WORK IN PROGRESS
- Event Loging System(Command Ran) -- WORK IN PROGRESS
- Optional Advanced Loging System -- WORK IN PROGRESS


## 🛠️ | How To Install
### 🖥️ | Windows
1. Download the [**Latest Release**](https://github.com/Whitty985playz/SER-Discord/releases) of SER Discord.
2. Move the SER Discord folder to `C:\Users\[USER]\AppData\Roaming\SCP Secret Laboratory\LabAPI\configs\Scripted Events Reloaded\` and extract the files in the folder.

![](https://i.postimg.cc/3JgY5WNs/image-2026-03-16-202831624.png)

3. You are done... Just follow the setup guide.

### 🖥️ | Linux

1. Download the [**Latest Release**](https://github.com/Whitty985playz/SER-Discord/releases) of SER Discord.
2. Move the SER Discord folder to `.config/SCP Secret Laboratory/LabAPI/configs/Scripted Events Reloaded/` and extract the files in the folder.

3. You are done... Just follow the setup guide.

## ⚙️ | How To Set Up -- Required Settings

**ALL** of these steps require the ***`SERDiscordConfig.txt`*** file.

![](https://i.postimg.cc/4xmGN8F5/image-2026-03-16-195857516.png)

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

> GUIDE SOON
