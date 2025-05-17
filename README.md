# UltraWide DUI Dark Theme
A Foobar2000 UltraWide Dark Theme for DUI and fits perfect for any 21:9 screens. 

![Image](https://github.com/user-attachments/assets/b7363970-9ea0-4d5d-a719-4c623c5035b9)
(*) _WORKS ONLY ON FOOBAR2000 32-BITS, UNTIL REMAINING COMPONENTS WILL BE UPDATED TO 64-BITS._

## COMPONENTS AND FEATURES:

- CUE Fixer
- Enhanced Playback Statistics
- JScript Panel 3 for Text Display / JS Playlist / Album art
- Last.fm Playcount Sync
- MusicBrainz Tagger
- On-Screen Display
- OpenLyrics
- AlbumArtDownloaderXUI through Run Services
- Scrobble to Last.fm (foo_scrobble)
- Shorten decoder
- MilkDrop 2.25 through SHPECK
- Spider Monkey Panel for Library Tree with 3 columns / Biography View
- TAK Decoder
- Taskbar Playback Progress Bar
- TTA Audio Decoder
- Waveform Minibar (mod) with playback time / remaining
- Media Library Search
- Selection Properties
- Oscilloscope
- Peak meter
- Spectogram
- Spectrum Analyzer
- VU meter
- Output selection

![Image](https://github.com/user-attachments/assets/12708a9b-206c-4303-8b5a-497f4dc89ae5)
(**) With On-Screen Display activated

(***) _PREVIOUS VERSIONS OF THE THEME INCLUDED THE DESKBAND CONTROLS COMPONENT, BUT UNFORTUNATELY IT IS STILL NOT POSSIBLE TO RUN IT ON WINDOWS 11 DUE TO THE MODIFICATIONS MADE TO THE TASKBAR._

## INSTALLATION AND CONFIGURATION

Compatible only with foobar 32-bit until remaining components will be updated to 64-bit!

1. Close foobar2000
3. Download the `UltraWide DUI Dark Theme` from <a href="https://github.com/RevenantX](https://mega.nz/file/Xd8lEDKB#o-qjRlYeLzkPMjoExtbyW_yBQZxlKSD_BlsjgNu__MI" target="_blank">HERE</a>.
4. Copy each folder into your foobar `profile` directory (`foo_spider_monkey_panel`, `configuration`, `user-components` and `Milkdrop`).
                                                                                 
6. + STANDARD foobar2000 installation: your foobar `profile` directory is in here: `%AppData%\foobar2000 or %AppData%\foobar2000-v2`
   + PORTABLE foobar2000 installation: your foobar `profile` directory is in a folder named `"profile"` inside your installation directory.

8. Install `fontawesome-webfont` from <a href="https://github.com/FortAwesome/Font-Awesome/raw/refs/heads/4.x/fonts/fontawesome-webfont.ttf" target="_blank">HERE</a>.
9. Run foobar2000
10. Extract `UltraWide DUI Dark Theme vX.x` from the `ZIP` and `import` in `FILE` > `PREFERENCES` > `DEFAULT USER INTERFACE` > `IMPORT THEME` or `DRAG & DROP` the `FILE` to foobar2000 `MAIN WINDOW`.
11. 📢 To Run `MILKDROP 2`: Configure the "Winamp directory" in `SHPECK` for the visualisations: ➡️ `FILE` > `PREFERENCES` > `VISUALISATIONS` > `SHPECK`. Click on the `...` button in the `TOP RIGHT CORNER` to browse and select the directory `FOOBAR_PROFILE_DIRECTORY\Milkdrop\Winamp` and click `AGREE`.
    Now, click `MilkDrop v2.25 / MilkDrop v2.25` and click `AGREE`. Then go to the `MilkDrop 2 TAB` of the THEME at `the RIGHT CORNER`. Right click and select `Autostart Plugin` > `MilkDrop v2.25 / MilkDrop v2.25`. ⚠️ Check `STOP WHEN HIDDEN` option is `UNCHECKED`

   🔵 OPTIONAL: To install some `PRESET PACKS` that are included: Extract `milkdrop 2 presets pack` to __MILKDROP 2__ subfolder `FOOBAR_PROFILE_DIRECTORY\milkdrop 2\Winamp\Plugins\milkdrop2\presets`

---------------------------------------------------------------------------------------------------------------

## SCRIPTS AND OTHER CONFIGURATIONS:

12. In `ZIP` file extract `AlbumArtDownloaderXUI-1.05` folder to the `profile` directory. Then click `FILE` > `PREFERENCES` > `TOOLS` > `RUN SERVICES`, click `Download Covers` > and in `PATH` add the next __STRING__: `FOOBAR_PROFILE_DIRECTORY\AlbumArtDownloaderXUI-1.05\AlbumArt.exe /ar "%album artist%" /al "%album%" /p "$replace(%path%,%filename_ext%,)%artist% - %album%.%%extension%%" /minSize 300 /coverType front`. Then click `OK`
13. Go to `FILE` > `PREFERENCE` and on `OPENLYRICS` component go to `SEARCH SOURCES` > `LOCAL FILES` and `MAKE` a subfolder on the `"profile"` folder to `DOWNLOAD AND SAVE 💾` the `LYRICS 🎵`

14. Enjoy!

## CREDITS

- <a href="https://github.com/RevenantX" target="_blank">RevenantX</a> CUE Fixer
- <a href="https://github.com/MordredKLB" target="_blank">MordredKLB</a> Enhanced Playback Statistics, MusicBrainz Tagger
- <a href="https://github.com/marc2k3" target="_blank">marc2k3</a> original foo_jscript_panel, Last.fm Playcount Sync
- <a href="https://github.com/kode54" target="_blank">kode54</a> On-Screen Display
- <a href="https://github.com/D3zmodos" target="_blank">D3zmodos</a> OpenLyrics
- <a href="https://github.com/Alex Vallat" target="_blank">Alex Vallat</a> AlbumArtDownloaderXUI
- <a href="https://github.com/gix" target="_blank">gix</a> foo_scrobble
- <a href="https://github.com/foosion" target="_blank">foosion</a> Shorten decoder
- <a href="https://github.com/Yirkha" target="_blank">Yirkha</a> SHPECK
- <a href="https://github.com/xeiraex" target="_blank">xeiraex</a> MilkDrop 2.25
- <a href="https://github.com/TheQwertiest" target="_blank">TheQwertiest</a> Spider Monkey Panel, which powers most of this theme foo_spider_monkey_panel
- <a href="https://github.com/Case" target="_blank">Case</a> Waveform Minibar (mod), TAK Decoder, Taskbar Playback Progress Bar, TTA Audio Decoder  
- <a href="https://github.com/WilB" target="_blank">WilB</a> Library Tree panel, Biography panel
