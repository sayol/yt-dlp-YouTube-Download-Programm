```pwsh
yt-dlp --js-runtimes node --remote-components ejs:github -o "%(playlist_title)s/%(playlist_index)02d - %(title)s.%(ext)s" "https://youtube.com/playlist?list=PLRScF6FPD0wKQFBH-A475tRXPh0W_Fqq-"
```