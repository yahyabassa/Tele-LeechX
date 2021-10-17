![FUZION LEECH](https://telegra.ph/file/213b587eee775e34ca221.jpg)
# FuZionX Leech Bot 
![GitHub Repo Stars](https://img.shields.io/github/stars/5MysterySD/Tele-LeechX?color=blue&style=plastic)
![GitHub Forks](https://img.shields.io/github/forks/5MysterySD/Tele-LeechX?color=green&style=plastic)
![GitHub Contributors](https://img.shields.io/github/contributors/5MysterySD/Tele-LeechX?style=plastic)
![GitHub Watchers](https://img.shields.io/github/watchers/5MysterySD/Tele-LeechX?style=plastic)
![GitHub issues](https://img.shields.io/github/issues/5MysterySD/Tele-LeechX?style=plastic)
![GitHub closed issues](https://img.shields.io/github/issues-closed/5MysterySD/Tele-LeechX?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/5MysterySD/Tele-LeechX?style=plastic)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/5MysterySD/Tele-LeechX?style=plastic)
![GitHub repo size](https://img.shields.io/github/repo-size/5MysterySD/Tele-LeechX?color=red?style=plastic)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/5MysterySD/Tele-LeechX?style=plastic)
[![Bot Support](https://img.shields.io/badge/Tele_LeechX-Support%20Group-blue)](https://t.me/FuZionXLeech)

**A Powerful Telegram Leech Bot** Modded by `MysterySD` to directly Leech to Telegram, with Multi Direct Links Support for Enhanced Leeching.

# Demo Group
<a href="https://t.me/FuZionXLeech"><img src="https://img.shields.io/badge/FuZion Leech Bot-2cb6e0?style=for-the-badge&logo=telegram&logoColor=white"></a>


# Features Supported :-
<details>
    <summary><b>Click Here For Description</b></summary>

## From Original Repo :
- Google Drive link cloning using gclone.(wip)
- Telegram File mirrorring to cloud along with its unzipping, unrar and untar
- Drive/Teamdrive support/All other cloud services rclone.org supports
- Unzip, Unrar, Untar while Leeching to Telegram .
- Custom file name (Used in Prefix on Every Item Leeched)
- Custom commands for Using in Telegram .
- Get total size of your working cloud directory
- You can also upload files downloaded from `/ytdlp` command to gdrive using `/ytdlp gdrive` command.
- You can also deploy this on your VPS .
- Option to select either video will be uploaded as document or streamable
- Added `/renewme` command to clear the downloads which are not deleted automatically.
- Added support for YouTube Playlist .
- Renaming of Telegram files support added. 😐
- Changing rclone destination config on fly (By using `/rlcone` in private mode)


## From Different Repos :
- Aria2 configs In Root
- Small FIX for Gclone
- Added Dynamic Config 
- Added Custom ToggleDoc and ToggleVid Commands
- Added Custom Rename Command via vars
- Added direct rclone.conf url in vars


## New In Repo :
- Dual Commands Usage (Both With / Without Bot Username)
- Auto Commands Set To BotFather in Telegram 
- New Torrent Search Support 
```
nyaa.si, sukebei, 1337x, piratebay,
tgx, yts, eztv, torlock, rarbg
```
- Extract Error Fixed
- UI Added for Improved User Experience with Easy to Use.
- Added New Status Bar using `/status` command. 
- Added Speedtest Support.
- Direct links Supported:
```
letsupload.io, hxfile.co, anonfiles.com, bayfiles.com, antfiles,
fembed.com, fembed.net, femax20.com, layarkacaxxi.icu, fcdn.stream,
sbplay.org, naniplay.com, naniplay.nanime.in, naniplay.nanime.biz, sbembed.com,
streamtape.com, streamsb.net, feurl.com, pixeldrain.com, racaty.net,
1fichier.com, 1drv.ms (Only works for file not folder or business account), solidfiles.com 
```
- Extract these filetypes and uploads Telegram 
```
ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, 
APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, 
HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, 
NTFS, RPM, SquashFS, UDF, VHD, XAR, Z.
```

</details>


# Variable Description :-


## Mandatory Variables :-
<details>
    <summary><b>Click Here For Description</b></summary>

* `TG_BOT_TOKEN`: Create a Bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API Token.

* `APP_ID`: Get this Value from [my.telegram.org/apps](https://my.telegram.org/apps).

* `API_HASH`: Get this Value from [my.telegram.org/apps](https://my.telegram.org/apps).
  * NOTE: If Telegram is blocked by your ISP, try Telegram to get the IDs.

* `AUTH_CHANNEL`: Create a Super(Means Changing it to `Visible` for `Chat History for New Members`) in Telegram, forward a Message from the Group to `@ShowJsonBot` to get this value.

* `OWNER_ID`: ID of the Bot Owner, He/She can be abled to access bot in bot only mode too(`Private mode`).

</details>


## Optional Configuration Variables :-

<details>
    <summary><b>Click Here For Description</b></summary>

* `DOWNLOAD_LOCATION`

* `MAX_FILE_SIZE`

* `TG_MAX_FILE_SIZE`

* `FREE_USER_MAX_FILE_SIZE`

* `MAX_TG_SPLIT_FILE_SIZE`

* `CHUNK_SIZE`

* `MAX_MESSAGE_LENGTH`

* `PROCESS_MAX_TIMEOUT`

* `ARIA_TWO_STARTED_PORT`

* `EDIT_SLEEP_TIME_OUT`

* `MAX_TIME_TO_WAIT_FOR_TORRENTS_TO_START`

* `FINISHED_PROGRESS_STR`

* `UN_FINISHED_PROGRESS_STR`

* `TG_OFFENSIVE_API`

* `CUSTOM_FILE_NAME`

* `LEECH_COMMAND`

* `YTDL_COMMAND`

* `GYTDL_COMMAND`

* `GLEECH_COMMAND`

* `TELEGRAM_LEECH_COMMAND`

* `TELEGRAM_LEECH_UNZIP_COMMAND`

* `PYTDL_COMMAND`

* `CLONE_COMMAND_G`

* `UPLOAD_COMMAND`

* `RENEWME_COMMAND`

* `SAVE_THUMBNAIL`

* `CLEAR_THUMBNAIL`

* `GET_SIZE_G`

* `UPLOAD_AS_DOC`: Takes two option True or False. If True file will be uploaded as document. This is for people who wants video files as document instead of streamable.

* `INDEX_LINK`: (Without `/` at last of the link, otherwise u will get error) During creating index, plz fill `Default Root ID` with the id of your `DESTINATION_FOLDER` after creating. Otherwise index will not work properly.

* `DESTINATION_FOLDER`: Name of your folder in ur respective drive where you want to upload the files using the bot.

</details>


# RClone Guide 

<details>
    <summary><b>Click Here For Description</b></summary>

- Set Rclone locally by following the official repo : https://rclone.org/docs/
- Get your `rclone.conf` file.
will look like this

```
[NAME]
type = 
scope =
token =
client_id = 
client_secret = 
```

- Copy `rclone.conf` file in the root directory (Where `Dockerfile` exists).

- Your config can contains multiple drive entries.(Default: First one and change using `/rclone` command)

</details>

# Deploying on Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Fhackertyus%2FTele-LeechX&envs=ENV%2CAPP_ID%2CAPI_HASH%2CTG_BOT_TOKEN%2CAUTH_CHANNEL%2COWNER_ID%2CTOGGLE_DOC%2CRENAME_COMMAND%2CLOG_COMMAND%2CSTATUS_COMMAND%2CLEECH_ZIP_COMMAND%2CLEECH_UNZIP_COMMAND%2CCHUNK_SIZE%2CARIA_TWO_STARTED_PORT%2CEDIT_SLEEP_TIME_OUT%2CMAX_TIME_TO_WAIT_FOR_TORRENTS_TO_STAR%2CFINISHED_PROGRESS_STR%2CUN_FINISHED_PROGRESS_STR%2CTG_OFFENSIVE_API%2CLEECH_COMMAND%2CSAVE_THUMBNAIL%2CCLEAR_THUMBNAIL%2CINDEX_LINK%2CYTDL_COMMAND%2CPYTDL_COMMAND%2CGET_SIZE_G%2CRCLONE_CONFIG%2CDESTINATION_FOLDER%2CCUSTOM_FILE_NAME%2CSPEEDTEST&optionalEnvs=TOGGLE_DOC%2CRENAME_COMMAND%2CLOG_COMMAND%2CSTATUS_COMMAND%2CLEECH_ZIP_COMMAND%2CLEECH_UNZIP_COMMAND%2CCHUNK_SIZE%2CARIA_TWO_STARTED_PORT%2CEDIT_SLEEP_TIME_OUT%2CMAX_TIME_TO_WAIT_FOR_TORRENTS_TO_STAR%2CFINISHED_PROGRESS_STR%2CUN_FINISHED_PROGRESS_STR%2CTG_OFFENSIVE_API%2CLEECH_COMMAND%2CSAVE_THUMBNAIL%2CCLEAR_THUMBNAIL%2CINDEX_LINK%2CYTDL_COMMAND%2CPYTDL_COMMAND%2CGET_SIZE_G%2CRCLONE_CONFIG%2CDESTINATION_FOLDER%2CCUSTOM_FILE_NAME%2CSPEEDTEST&ENVDesc=Setting+this+to+ANYTHING+will+enable+Webhooks+when+in+env+mode&APP_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&TG_BOT_TOKENDesc=Get+this+value+from+%40BotFather+by+Making+New+Bot+and+Paste+the+API+token.&AUTH_CHANNELDesc=Should+be+an+integer.+The+BOT+API+ID+of+the+Telegram+Group%2C+Where+the+Bot+should+work.%2C+Put+Group+ID.+Multiple+ID+separated+by+Single+Space&OWNER_IDDesc=Should+be+an+integer.+ID+of+owner+of+bot.+Get+it+by+sending+%2Finfo+to+%40MissRose_Bot&TOGGLE_DOCDesc=Enter+your+custom+toggle+command+like+togglevid1%40botname+and+so+on.+Default+is+%2Ftogglevid.&RENAME_COMMANDDesc=Enter+your+custom+rename+command+like+rename1%40botname+and+so+on.+Default+is+%2Frename.&LOG_COMMANDDesc=Enter+your+custom+log+command+like+log1%40botname+and+so+on.+Default+is+%2Flog.&STATUS_COMMANDDesc=Enter+your+custom+status+command+like+status1%40botname+and+so+on.+Default+is+%2Fstatus.&LEECH_ZIP_COMMANDDesc=Enter+your+custom+zip+command+like+archive1%40botname+and+so+on.+Default+is+%2Fleechzip.&LEECH_UNZIP_COMMANDDesc=Enter+your+custom+unzip+command+like+extract%40botname+and+so+on.+Default+is+%2Fleechunzip.&CHUNK_SIZEDesc=Should+be+an+integer&ARIA_TWO_STARTED_PORTDesc=Should+be+an+integer.+The+port+on+which+aria2c+daemon+must+start%2C+and+keep+listening.&EDIT_SLEEP_TIME_OUTDesc=Should+be+an+integer.+Number+of+seconds+to+wait+before+editing+a+message.+Put+between+from+6+-+15+else+the+Bot+Crashes+%F0%9F%A5%B2&MAX_TIME_TO_WAIT_FOR_TORRENTS_TO_STARDesc=should+be+an+integer.+Number+of+seconds+to+Wait+before+Cancelling+a+torrent.&FINISHED_PROGRESS_STRDesc=Should+be+a+Single+Character.+Get+any+Cool+Icon.&UN_FINISHED_PROGRESS_STRDesc=Should+be+a+Single+Character.+Get+any+Cool+Icon.&TG_OFFENSIVE_APIDesc=should+be+an+URL+accepting+the+FormParams+%7Bi%7D%2C+%7Bm%7D%2C+and+%7Bt%7D&LEECH_COMMANDDesc=Enter+your+Custom+leech+command+like+leech1%40botname+and+so+on.+Default+is+%2Fleec&SAVE_THUMBNAILDesc=For+Custom+Save+thumbnail+Command.+Default+is+%2Fsavethumbnail&CLEAR_THUMBNAILDesc=For+Custom+Delete+Thumbnail+Command.+Default+is+%2Fclearthumbnail&INDEX_LINKDesc=Enter+your+index+link%3A&YTDL_COMMANDDesc=Enter+your+custom+ytdl+command+like+ytdl1%40botname+and+so+on.+Default+is+%2Fytdl.&PYTDL_COMMANDDesc=Enter+your+custom+pytdl+command+like+pytdl1%40botname+and+so+on.+Default+is+%2Fpytdl.&GET_SIZE_GDesc=Enter+your+custom+getsize+command+like+getsize%40urgroupname+and+so+on.+Default+is+%2Fgetsize.&RCLONE_CONFIGDesc=Enter+your+copied+text+from+rclone+config.+Compulsory+for+%2Fgleech+as+well+as+%2Ftleech+command+&DESTINATION_FOLDERDesc=Enter+your+Cloud+folder+NAME%28not+ID%F0%9F%98%85%29+in+which+you+want+to+upload%2Fstore+your+files.&CUSTOM_FILE_NAMEDesc=Fill+with+name+you+want+to+prefix+the+file+name+like+ur+channel+username%F0%9F%99%8A%2C+keep+empty+for+do+nothing%2C+but+add+to+ur+config+vars+even+without+input.&SPEEDTESTDesc=For+Custom+Speedtest+Command.+Default+is+%2Fspeedtest&ENVDefault=ANYTHING&TOGGLE_DOCDefault=toggledoc&RENAME_COMMANDDefault=rename&referralCode=TEST)

# Deploying on Heroku
- Deploying on Heroku Indirectly `Supported`, Please Don't Abuse it or Share this Repo like Anything !!

<p><a href="https://github.com/hackertyus/Tele-LeechX/blob/master/heroku-deploy.md"> <img src="https://img.shields.io/badge/Deployment%20Guide-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>


## Bot Commands Available For Repo:-

<details>
    <summary><b>Click Here For Description</b></summary>

🤖Available BOT  Commands | Usage
------------ | -------------
|`/rclone`| This will change your drive config on fly.(First one will be def `/gclone`..This command is used to clone gdrive files or folder using gclone.-Syntax- `[ID of the file or folder][one space][name of your folder only(If the id is of file, don't put anything)]` and then reply /gclone to it.\
|`/log`| This will send you a txt file of the logs.
|`/ytdlp`| This command should be used as reply to a [supported link](https://ytdl-org.github.io/youtube-dl/supportedsites.html)
|`/pytdlp`| This command will download videos from youtube playlist link and will upload to telegram.
|`/gytdlp`| This will download and upload to your cloud.
|`/gpytdlp`| This download youtube playlist and upload to your cloud.
|`/leech`| This command should be used as reply to a magnetic link, a torrent link, or a direct link. this command will SPAM the chat and send the downloads a seperate files, if there is more than one file, in the specified torrent
|`/leechzip`| This command should be used as reply to a magnetic link, a torrent link, or a direct link. [This command will create a .tar.gz file of the output directory, and send the files in the chat, splited into PARTS of 1024MiB each, due to Telegram limitations]
|`/gleech`| This command should be used as reply to a magnetic link, a torrent link, or a direct link. And this will download the files from the given link or torrent and will upload to the cloud using rclone.
|`/gleechzip` | This command will compress the folder/file and will upload to your cloud.
| `/leechunzip`| This will unarchive file and dupload to telegram.
|`/gleechunzip`| This will unarchive file and upload to cloud.
|`/tleech`| This will mirror the telegram files to ur respective cloud cloud.
|`/tleechunzip`| This will unarchive telegram file and upload to cloud.
|`/getsize`| This will give you total size of your destination folder in cloud.
|`/renewme`| This will clear the remains of downloads which are not getting deleted after upload of the file or after /cancel command.
| `/rename`| u can add custom name as prefix of the original file name...Like if your file name is `gk.txt` uploaded will be what u add in `CUSTOM_FILE_NAME` + `gk.txt`..And also added custom name like...You have to pass link as ..`www.download.me/gk.txt new.txt`..the file will be uploaded as `new.txt`.
| `/toggledoc` | it used for toggling to be files if shall it be uploaded as doc via direct inchat cmd...**any users can now choose if their files will be upload as doc or streamabe...**
| `/togglevid` | it used for toggling to be files if shall it be uploaded as vid via direct inchat cmd...**any users can now choose if their files will be upload as doc or streamabe...**
| `/status`| show bot stats and concurrent downloads
| `/savethumbnail`| save the thumbnail
| `/clearthumbnail`| clear the thumbnail
| `/help`| send help

</details>


### Commands Available :-
- Set the Custom Commands in Heroku with Respective Var like leech1 or So on . .

<details>
    <summary><b>Click Here For Description</b></summary>

---
    leech - leech any torrent/magnet/direct-download link to Telegram 
	leechunzip - This will unarchive file and upload to telegram.
    leechzip - leech any torrent/magnet/direct-download link to Telegram and Upload It as .tar.gz acrhive...
    ytdlp - This command should be used as reply to a supported link
    pytdlp - This command will download videos from youtube playlist link and will upload to telegram.	
	toggledoc - choose whether the file shall be uploaded as doc or not
    togglevid - choose whether the file shall be uploaded as streamable or not
	savethumbnail - save thumbnail
    clearthumbnail - clear thumbnail
    tleech - This will mirror the telegram files to ur respective cloud .
    tleechunzip - This will unarchive telegram file and upload to cloud.
    gclone - This command is used to clone gdrive files or folder using gclone
    gytdlp - This will download and upload to your cloud.
    gpytdlp - This download youtube playlist and upload to your cloud.
    gleech - leech any torrent/magnet/direct-download link to cloud
    gleechzip - leech any torrent/magnet/direct-download link to Cloud and Upload It as .tar.gz acrhive...
    gleechunzip - This will unarchive file and upload to cloud.
    getsize - This will give you total size of your destination folder in cloud.
    rename - rename the file 
    speedtest - Check Server Speedtest 
    help - send help 
    status - show bot stats and concurrent downloads
    renewme - clear all downloads (admin only)⚠️
    log - This will send you a txt file of the logs.(admin only)⚠️
    rclone - This will change your drive config on fly.(First one will be default)--(admin only)⚠️
---

</details>


## Give A ⭐ Star ⭐ Before You Go Anywhere 


## Credits Goes To 🎖🏆  . . .

<details>
    <summary><b>Click Here For Description</b></summary>

* [`MysterySD`](https://github.com/5MysterySD) Meh 🧐 For Speedtest, Direct Link Support, More in Future. 
* [`KGK06`](https://github.com/KGK06) For Merging Different Repos 
* [`XcodersHub`](https://github.com/XcodersHub) For The Aria2 Config & Little More
* [`GautamKumar`](https://github.com/gautamajay52/TorrentLeech-Gdrive) 😬
* [`SpEcHiDe`](https://github.com/SpEcHiDe/PublicLeech) for his wonderful code😚
* [`Rclone Team`](https://rclone.org) for theirs awesome tool☁️
* [`Dan Tès`](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
* [`Robots`](https://telegram.dog/Robots) for their [@UploadBot](https://telegram.dog/UploadBot)
* [`@AjeeshNair`](https://telegram.dog/AjeeshNait) for his [torrent.ajee.sh](https://torrent.ajee.sh)
* [`@gotstc`](https://telegram.dog/gotstc), `@aryanvikash`, [`@HasibulKabir`](https://telegram.dog/HasibulKabir) for their TORRENT groups

</details>

