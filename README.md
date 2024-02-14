# COLORFUL

---
A port of the COLORFUL bigbox theme to Pegasus.

[![Video](.meta/screenshots/CollectionsWheel.png)](https://youtu.be/O1Q5IVHPxeI)
![CollectionDetails](.meta/screenshots/CollectionsDetails.png)
![GameListView](.meta/screenshots/GamesListView.png)

---

Video assets for the Collections pages **are required** to be downloaded separately (due to the size) or else there will only be static images. 

1080P versions for many platforms (60+), renamed for this theme [are available here](https://mega.nz/folder/6VByEKTS#I7yela1-PrAzneLCQkw1jg).
Additional platforms can be found at the [creators page](https://forums.launchbox-app.com/files/file/1958-colorful-platform-video-set/).

Collections must be named using the shortnames listed below to work properly or can be edited in the collectiondata.qml

Platform shortnames:
3do, 3ds, amiga, android, arcade, atari2600, atari5200, atari7800, atarijaguar, atarilynx, atomiswave, c64, cdi, colecovision, cps1, cps2, cps3, dos, dreamcast, famicom, fbneo, fds, gamecube, gamegear, gb, gba, gbc, genesis, gw, intellivision, mame, mastersystem, msx, mvs, n64, naomi, nds, neogeo, neogeocd, nes, ngp, ngpc, odyssey2, pcecd, pcengine, pico8, pokemini, ps2, psp, psx, saturn, scummvm, sega32x, segacd, sfc, sg1000, snes, supergrafx, switch, tg16, tgcd, vboy, vectrex, vita, wii, wswan, wswanc, x68000, zxspectrum

---

## Metadata used in the theme:
- `boxFront`
- `screenshot`
- `wheel`
- `video`

---

## Changelog:
- 0.10 Initial release
- 0.11 Added device images and fallback for when no collection videos exist, fixed loading of game screenshots in game wheel view when no game video exists
- 0.12 Updated collections video and image sources to check against common platform shortname aliases to be less dependant on following exact naming convention, added Accept button options for A, B, cross (X) and circle (O) covering Xbox/Nintendo/PS layouts and regional variations

This has only been tested on an AYN Odin 2 but reach out if anything is not working as expected or you have suggestions!

---

## To Do:
- [x] Fall back images for no collection video
- [x] Add shortname alias function for image/video source references 
- [ ] Mark as favorite button
- [ ] Add favorite icons to game views
- [ ] Touch controls
- [ ] All/Favorites/Recents collections
- [ ] Battery/clock
- [ ] Shortcut keys to change collection index from game view
- [ ] Shortcut keys to move to start/end of list / skip letter
- [ ] Nav sounds
- [ ] Better color matching between videos and rendered text/shapes
- [ ] Favorites filter
- [ ] Favorites on top toggle
- [ ] Fix game auto scroll on first transition to list view

---

## Credits:
- viking - creator of the [COLORFUL media set and theme](https://forums.launchbox-app.com/files/file/2081-colorful-bigbox-theme/)
- Dan Patrick - [v2 Platform Logos](https://forums.launchbox-app.com/files/file/3402-v2-platform-logos-professionally-redrawn-official-versions-new-bigbox-defaults/page/2/?tab=comments#comment-12469)
- All the Pegasus theme creators that I have borrowed ideas from especially [epic-memories-theme](https://github.com/FrenchGithubUser/epic-memories-theme), [retromega-sleipnir](https://github.com/TigraTT-Driver/shinretro) and [shinretro
](https://github.com/y-muller/retromega-sleipnir)
