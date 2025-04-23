# Video Downloader


Download videos from websites with an easy-to-use interface.
Provides the following features:

  * Convert videos to MP3
  * Supports password-protected and private videos
  * Download single videos or whole playlists
  * Automatically selects a video format based on your quality demands

Based on [yt-dlp](https://github.com/yt-dlp/yt-dlp).



## Screenshots

![screenshot 1](https://raw.githubusercontent.com/Unrud/video-downloader/master/screenshots/1.png)

![screenshot 2](https://raw.githubusercontent.com/Unrud/video-downloader/master/screenshots/2.png)

![screenshot 3](https://raw.githubusercontent.com/Unrud/video-downloader/master/screenshots/3.png)

## Hidden configuration options

The behavior of the program can be tweaked with GSettings.

### Automatic Subtitles

List of additional automatic subtitles to download. The entry `all` matches all languages.

The default is `[]`.


## Debug

To display messages from **yt-dlp** run program with the environment variable `G_MESSAGES_DEBUG=yt-dlp`.

To display information about GOBject references, start the program with the environment variable `G_MESSAGES_DEBUG=gobject-ref`.
