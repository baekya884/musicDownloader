# Music Downloader

## download music easily
this is music downloader as based on youtube-dl(https://github.com/ytdl-org/youtube-dl) and ffmpeg(https://github.com/FFmpeg/FFmpeg)  

### features  
- automatically add album cover, lyrics and other id3v2 tags (artist, song type, etc)  
- store selected musics in sql lite database

## how to use?

1. choose music in top 100 or bugs search tab
2. in youtube search page select youtube video about selected music item
3. then at stored youtube page select download path and click download button
4. check your download directory then you will see the music file.

![Alt Text](./static/review.gif)  


## how to build
```
1. first yarn install

2. put your youtube api key in conf/config.json
{
  "youtubeApiKey": "{your_api-key}"
}

3. yarn run electron:build

4. check your dist_electron directory 
```


## to develop

```
1. first yarn install

2. put your youtube api key in conf/config.json
{
  "youtubeApiKey": "{your_api-key}"
}

3. yarn run electron:serve
```