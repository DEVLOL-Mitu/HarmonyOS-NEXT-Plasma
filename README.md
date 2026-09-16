# HarmonyOS NEXT Surge for KDE Plasma

Global Plasma theme built from the Huawei **Surge HWT pack. Huawei adaptive icons are composited and published under the KDE / freedesktop names Plasma apps actually use. Window chrome, colors, wallpaper, and Look-and-Feel follow HarmonyOS 5 NEXT desktop windows (large radius, light/dark surfaces, right-side caption buttons, floating dock).

## What you get

| Piece | Name |
|---|---|
| Global theme | HarmonyOS NEXT Surge / Surge Dark |
| Icons | HarmonyOS-Surge (inherits Breeze for anything not in the pack) |
| Windows | Aurorae **HarmonyOS-NEXT** / **HarmonyOS-NEXT-Dark** |
| Colors | HarmonyOS NEXT (accent `#0A59F7`, close/error `#E75746`) |
| Wallpaper | Surge |
| Layout | Centered floating bottom dock (optional when applying the global theme) |

## Build and install

```bash
python3 scripts/build_theme.py
./install.sh
```

Then **System Settings â†’ Appearance â†’ Global Theme** â†’ HarmonyOS NEXT Surge.

Icons also appear on their original Android package ids (`com.huawei.camera.png`, â€¦) plus aliases such as `org.kde.dolphin`, `org.kde.systemsettings`, `org.kde.gwenview`.

Re-run the build after editing `ALIASES` in `scripts/build_theme.py` to cover more apps. The `Icon=` key is in each appâ€™s `.desktop` file under `/usr/share/applications/`.
