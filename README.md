# teetube-db

Global video database for [TeeTube](https://github.com/m09l6d0ur13ii/teetube) — the community DDNet/Teeworlds video tracker.

## Structure

```json
{
  "version": 1,
  "updatedAt": "ISO timestamp",
  "updatedBy": "github username",
  "videos": {
    "YOUTUBE_VIDEO_ID": {
      "title": "...",
      "author": "...",
      "views": "125000",
      "likes": "2100",
      "date": "2024-03-15",
      "thumbnail": "https://i.ytimg.com/vi/ID/hqdefault.jpg",
      "tags": {
        "game": ["ddnet"],
        "video": ["speedrun"],
        "mode": ["ddrace"],
        "gameplayer": ["real"]
      },
      "maps": ["Multeasymap"],
      "players": ["Rajh"],
      "clans": ["aura"],
      "addedBy": "m09l6d0ur13ii",
      "addedAt": "2026-07-02T00:00:00Z"
    }
  },
  "moderators": ["m09l6d0ur13ii"]
}
```

## Read via jsDelivr CDN

```
https://cdn.jsdelivr.net/gh/m09l6d0ur13ii/teetube-db@main/database.json
```

## Write access
Only moderators listed in `moderators` field can write to this database via the TeeTube Extension admin panel.
