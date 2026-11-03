# RimWorld mod media

Images and GIFs for Fysh's RimWorld mod pages on the Steam Workshop. Workshop descriptions can
only show images from a public URL, so they live here.

## Layout

One folder per mod, named after the mod's description file (`_workshop/descriptions/<name>.bbcode.txt`):

| Folder | Mod |
|---|---|
| `isthisbetter/` | Is This Better? |
| `universalversionpatch/` | Universal Version Patch |
| `empireroomfix/` | VFE Empire - Room Tracker Fix |
| `quickload/` | QuickLoad |
| `betterweather/` | Better Weather |
| `accurateeras/` | Accurate Eras |
| `shared/` | used on every page (banners, "more mods from me" thumbnails) |

Inside each mod folder:

- `inline/`: images and GIFs embedded in the description, numbered in page order:
  `01-hover-verdict.png`, `02-who-should-use.gif`, ...
- `gallery/`: full-size shots for the page's own image gallery (Steam hosts those, they are kept
  here as the source copy).

## Rules

- **Never rename or delete a file that a published page links to.** Old page versions and
  translations keep pointing at it. Add a new file instead (`01-hover-verdict-v2.png`).
- Link with the raw URL:
  `https://raw.githubusercontent.com/Fysh-ball/rimworld-mod-media/main/<mod>/inline/<file>`
- Keep GIFs under about 5 MB and 900 px wide; Steam scales them down anyway.
- Each mod's folder is edited only by whoever is working on that mod, so pushes don't collide.
  Pull before you push.
