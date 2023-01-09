# Music App Tutorial
Build a simple music app with HTML, CSS, and JavaScript

## TLDR;
- Semantic HTML
- CSS
- Vanilla JavaScript with arrow functions

### Demo link:

### Overview
In this tutorial, you'll create a simple music application using HTML, CSS, and JavaScript.

- Play / Pause song
- Select song from playlist
- Skip to next song
- Skip to previous song
- Seek song
- Expand / Collapse player

### Data Array Objects Format
const data = [
    {
        album: "name of album",
        title: "name of song",
        artist: "name of artist",
        duration: "duration of song",
        source: "song MP3 file",
        poster: "song player image",
        thumb: "song playlist image"
    },
    { ... }
]

### Source files
Images:
- Each song has it's own image with two copies of that image (poster / thumb)
- Poster is a larger version and is used for the player
- Thumb is a smaller version of the same image and is used for the playlist
- For simplicty, the file names start at 0 and are located in the images folder, ex:

images/poster-0.webp, images/poster-1.webp, images/poster-2.webp...
images/thumb-0.webp, images/thumb-1.webp, images/thumb-2.webp...

Songs:
- Each song has it's own MP3 file and follow the same naming convention as the images, except in the songs folder, ex:

songs/song-0.mp3, songs/song-1.mp3, songs/song-2.mp3

Happy coding!