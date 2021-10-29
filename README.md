[![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video)

[![badge](https://img.shields.io/github/stars/apivideo/videoUploadToDiscord?style=social)](https://github.com/apivideo/videoUploadToDiscord)

[![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)

![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)

api.video is an API that encodes on the go to facilitate immediate playback, enhancing viewer streaming experiences across multiple devices and platforms. You can stream live or on-demand online videos within minutes.

# videoUploadToDiscord
NodeJS app to upload videos to a Discord Bot


## Installation 

Clone github repo
add environmental variables
install node dependancies
node src/index.js

## To run on YOUR Discord channel

1. connect the apivideo_uploader bot to your channel:
https://discord.com/oauth2/authorize?client_id=780911671153000479&scope=bot

2. In Discord, get the Channel ID:  
   * Trun on developer mode - click the settings next to your name
   * appearance - scroll to the bottom - enable developer mode
   * now right click the channel you want the bot in, and right click. Cop[y the id
   

On the webpage - name and describe the video - paste in the channelId.  Then select your video. IT will upload and post automatically to your Discord channel.

This app uses api.video delegated tokens, and posts to the sandbox - where videos are watemarked (and removed after 72 hours).  Create your own account & [deletgated token](https://api.video/blog/tutorials/uploading-large-files-with-javascript) at [api.vuide](https://api.video).
