audiojs-playlist-skin
=====================

<a href="https://github.com/kolber/audiojs">audio.js</a> powered audio playlist, with volume, track and skipto capabilities

Full <a href="http://www.briandanchilla.com/interests/music/spotlight/songs" target="_blank">demo</a>

![Demo Screenshot] (https://raw.githubusercontent.com/bdanchilla/audiojs-playlist-skin/master/screenshot.jpg "Demo Screenshot")

Basic usage is in index.html:

```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>audiojs Playlist Skin Demo</title>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css">
    <link rel="stylesheet" href="./css/playlist.css">
</head>
<body>
    
    <audio preload></audio>
    <div id="playlist-container">
        <ol id="playlist">
            <li><a href="#" data-src="your-first-track.mp3">your first track</a></li>
            <li><a href="#" data-src="your-second-track.mp3">your second track</a></li>
        </ol>
    </div>

    <script src="https://code.jquery.com/jquery-2.1.1.min.js"></script>
    <script src="./audiojs/audio.min.js"></script>
    <script src="./js/playlist.js"></script>
</body>
</html>
```
