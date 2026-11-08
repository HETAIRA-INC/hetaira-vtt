# hetaira-vtt

Subtitles for the Hetaira archive.

```
vtteditor.html                              Timing Studio: the subtitle editor
<artist-uuid>/vtt/<record-uuid>.vtt         word-timed WebVTT, played by hetaira-fe/vttplayer.html
<artist-uuid>/ProjectFiles/<record-uuid>.json   editor project (to edit the timing again later)
```

Create or edit a subtitle from the admin (record page → **Open in VTT editor**, or
`http://localhost:3000/vtt/vtteditor.html?artist=<artist-uuid>&uuid=<record-uuid>`), then **Save to archive**. Files in this repo are
written by the admin; commit and push them. Details: [`../docs/VTT.md`](../docs/VTT.md).
