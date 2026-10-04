# Dense Sidebar

A compact-density mod for Zen Browser's sidebar.

Instead of tuning text, icons and row heights independently, **Dense Sidebar** lets you choose a size for each type of sidebar row. The mod derives matching font and icon sizes automatically.

## Controls

- **Tab row size** — ordinary tabs
- **Folder row size** — folders, including the Zen folder icon
- **New Tab / utility row size** — New Tab, Settings, Troubleshooting, the current workspace header and the normal sidebar URL/search row

Every control starts with **Standard (Zen default)**. In that mode Dense Sidebar does not override Zen's native styling for that row type.

## Size scale

| Row | Font | Icon |
| ---: | ---: | ---: |
| 18 px | 8 px | 12 px |
| 20 px | 9 px | 13 px |
| 22 px | 10 px | 14 px |
| 24 px | 11 px | 16 px |
| 26 px | 12 px | 17 px |
| 28 px | 13 px | 18 px |
| 30 px | 14 px | 20 px |
| 32 px | 15 px | 21 px |
| 34 px | 16 px | 22 px |
| 36 px | 17 px | 24 px |

A good compact starting point is **22 px tabs / 24 px folders / 24 px utilities**.

## Behavior

The current workspace header and the normal sidebar URL/search row follow the **New Tab / utility row size**.

Zen's floating/breakout URL bar is intentionally left untouched so search/edit overlays keep their native geometry.

## Local installation

Place chrome.css and preferences.json under:

    <Zen profile>/chrome/zen-themes/dense-sidebar/

Register the mod in the profile-level zen-themes.json. An example entry is provided in zen-themes-entry.json.

## Version

Current version: **2.0.3**

### 2.0.3
- Added extra spacing between ordinary tab icons and tab text.

### 2.0.2
- Matched workspace indicator height to New Tab / utility rows.
- Scaled workspace and New Tab icons with the selected row size.

### 2.0.1
- Applied New Tab / utility density to the workspace header and normal sidebar URL/search row.

## Author

**homofaber-tech**

## License

MIT
