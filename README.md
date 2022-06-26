# youtube-dl

## Download mp3 from playlist
```code
youtube-dl -f "bestaudio/best" -ciw -o "%(title)s.%(ext)s" -v --extract-audio --audio-format mp3 --audio-quality 0  --yes-playlist [url playlist]
```

## Download mp3 from a video
```code
youtube-dl --extract-audio --audio-format mp3  [url video]
```

## Download mp3 from playlist [DEPRECATED]
```code
youtube-dl -x --audio-format mp3 [url playlist]
```

## Donwload all videos from playlist
```code
youtube-dl -i [url_playlist]
```

