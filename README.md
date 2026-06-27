# 864beat

GitHub Pages ready folder.

## Files

- `index.html`: game entry page
- `game.html`: same game page, explicit file name
- `editor.html`: chart editor
- `songs/index.json`: song list used by the selection screen
- `songs/<song folder>/`: chart, audio, and background assets

## Add a song

1. Create a folder under `songs/`.
2. Put `.2d`, audio, and optional background image in that folder.
3. Add an entry to `songs/index.json`.

Example:

```json
{
  "title": "Song Title",
  "artist": "Artist",
  "folder": "SongFolder",
  "chart": "chart.2d",
  "audio": "song.ogg",
  "updated": "2026-06-27"
}
```

## Publish

Upload this folder's contents to a GitHub repository and enable GitHub Pages for the repository root.
