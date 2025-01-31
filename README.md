<div align="center">
    <h1>Discord Backup</h1>
    <p>☁️ Backup and Restore your Discord Account in minutes.</p>
    <img src="https://img.shields.io/github/license/ItsChasa/Discord-Backup?style=flat&logo=appveyor">
    <img src="https://img.shields.io/github/downloads/ItsChasa/Discord-Backup/total?style=flat&logo=appveyor">
    <img src="https://img.shields.io/github/stars/ItsChasa/Discord-Backup?style=flat&logo=appveyor">
    <img src="https://img.shields.io/github/forks/ItsChasa/Discord-Backup?style=flat&logo=appveyor">
    <img src="https://sonarcloud.io/api/project_badges/measure?project=itschasa_Discord-Backup&metric=ncloc"/>
    <br>
    <img src="https://github.com/ItsChasa/Discord-Backup/blob/main/img/backup-demo.gif">
</div>



## Support + Community
[Discord Server](https://chasa.wtf/discord) | [Telegram Chat](https://chasa.wtf/telegram) | [Website](https://chasa.wtf/)


## Disclaimer 
The automation of Discord Accounts also known as self-bots is a violation of Discord Terms of Service & Community Guidelines and will result in your account(s) being terminated. Discretion is adviced. I will not be responsible for your actions. Read about Discord [Terms Of Service](https://discord.com/terms) and [Community Guidelines](https://discord.com/guidelines) here.


## **Features**:
### Automatic
These can be done by the program:
- Backup Servers
- Backup Group Chats
- Backup Avatar, Banner and Bio
- Backup + Restore Server Folders
- Backup + Restore Relationships (Friends, Blocked, etc)
- Auto-Backup on PC Startup
- Colour Customisation
### Manual
You will have to do this yourself:
- Restore Servers
- Restore Group Chats
- Restore Avatar, Banner and Bio


## Installation
### Using Binary EXE (Easier)
1. Download the zip for your Operating System from [Releases](https://github.com/itschasa/Discord-Backup/releases)
2. Unzip the contents into a folder
3. Run the exe

### Using Source
1. Install [Python 3.9.10](https://www.python.org/downloads/release/python-3910/) (should work with other versions)
2. Download source with the green `Code` button, then `Download ZIP`
3. Unzip the contents into a folder
4. Run in your command prompt:
```
pip install -r requirements.txt
```
5. Run main.py, either by double clicking or with command prompt (preferred way):
```
python main.py
```


## Notes / FAQ:
### Restoring Servers + Group Chats + Server Folders
Because of Discord's last resorts of using hCaptcha to stop people self-botting on Discord, I've decided its best to stop this program needing a captcha key.
- The program will create a server with all the old server invites in them, sorted into the folders from the old account.
- You simply just join them, when you need to.
- After you have joined all the servers, you can use the restore module to only restore folders.

### Group Chat Invites
Group Chat Invites are a bit scuffed on Discord.
- Server Invites will still be active if you leave the server.
- However, Group Chat Invites will not work **if you leave** the Group Chat.
- Meaning, if you leave the group chat after a backup, and before a term, then you won't be able to join that group chat back.

### Can I backup/restore an account which is already termed?
No. You can't, and never will be able to. Stop asking this.

### There's a feature I want to suggest.
Suggest it in the issues tab. I will probably add it.

### I keep getting an error, help!
Make an issue in the issue tab, or ask in the Community Servers.
