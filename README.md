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
2. Download the `UltraWide DUI Dark Theme` from <a href="https://github.com/Gabohar/UltraWide-DUI-Dark-Theme/releases" target="_blank">HERE</a>
3. Copy each folder into your foobar `profile` directory (`foo_spider_monkey_panel`, `configuration` and `user-components`)
                                                                                 
    + STANDARD foobar2000 installation: your foobar `profile` directory is in here: `%AppData%\foobar2000 or %AppData%\foobar2000-v2`
    + PORTABLE foobar2000 installation: your foobar `profile` directory is in a folder named `"profile"` inside your installation directory

 4. Install `fontawesome-webfont` from <a href="https://github.com/FortAwesome/Font-Awesome/raw/refs/heads/4.x/fonts/fontawesome-webfont.ttf" target="_blank">HERE</a>
 5. Run foobar2000
 6. Extract `UltraWide DUI Dark Theme vX.x.fth` from the `ZIP` and `import` in `FILE` > `PREFERENCES` > `DEFAULT USER INTERFACE` > `IMPORT THEME` or `DRAG & DROP` the `FILE` to foobar2000 `MAIN WINDOW`.
 7. 📢 To Run `MILKDROP 2`: Download it from <a href="https://github.com/Gabohar/UltraWide-DUI-Dark-Theme/releases" target="_blank">HERE</a> ➡️ Extract the folder to your foobar `profile` directory
 8. Donwload and Install `DirectX End-User Runtime` from <a href="https://www.microsoft.com/en-us/download/details.aspx?id=35" target="_blank">HERE</a>
 9. Configure the "Winamp directory" in `SHPECK` for the visualisations: ➡️ `FILE` > `PREFERENCES` > `VISUALISATIONS` > `SHPECK`
    Click on the `...` button in the `TOP RIGHT CORNER` to browse and select the directory `FOOBAR_PROFILE_DIRECTORY\milkdrop v2.25c\winamp` and click `OK`
 10. + Now, click `MilkDrop v2.25c / MilkDrop v2.25c` and click `OK`. Then go to the `MilkDrop 2 TAB` of the `THEME` at `the RIGHT CORNER`. Right click and select `Autostart Plugin` > `MilkDrop v2.25c / MilkDrop v2.25c`
    + ⚠️ Check `STOP WHEN HIDDEN` option is `UNCHECKED`
 11. 🔵 OPTIONAL: To install some `PRESETS`: Extract `milkdrop 2 presets pack` from <a href="https://mega.nz/file/CIM1mKwT#cur7PuCcy_t7dBXK13zzcuc9X5LyaApNLqCZ97QWwGQ" target="_blank">HERE</a> to `MILKDROP 2` subfolder `FOOBAR_PROFILE_DIRECTORY\milkdrop v2.25c\winamp\plugins\milkdrop2\presets`
 
 12. For Library Tree to work properly, you MUST have your `MUSIC LIBRARY` configured. This theme comes __preconfigured__ to display artists and albums based on a `directory structure`, __not metadata__. You can configure it anyway:

     Click on the `...` button in the `TOP RIGHT CORNER` of any of the 3 columns and then `VIEWS`.
    
---------------------------------------------------------------------------------------------------------------

## SCRIPTS AND OTHER CONFIGURATIONS:

13. To activate `AlbumArtDownloaderXUI-1.05` on foobar2000 download it from <a href="https://github.com/Gabohar/UltraWide-DUI-Dark-Theme/releases" target="_blank">HERE</a> and __EXTRACT__ the folder to the `profile` directory. Then click `FILE` > `PREFERENCES` > `TOOLS` > `RUN SERVICES`, click `Download Covers` > and in `PATH` add the next __STRING__:

`FOOBAR_PROFILE_DIRECTORY\AlbumArtDownloaderXUI-1.05\AlbumArt.exe /ar "%album artist%" /al "%album%" /p "$replace(%path%,%filename_ext%,)%artist% - %album%.%%extension%%" /minSize 300 /coverType front`. Then click `OK`

14. To run `AlbumArtDownloaderXUI-1.05` on foobar2000: __Right click__ an _album_ or _track_ in your _PLAYLIST_ and click on `Run Service` > `Download Covers` ⏬
15. Go to `FILE` > `PREFERENCES` and on `OPENLYRICS` component go to `SEARCH SOURCES` > `LOCAL FILES` and `MAKE` a subfolder in the `"profile"` folder to `DOWNLOAD AND SAVE 💾` the `LYRICS 🎵`

    In the same way, in `SEARCH SOURCES` you can order the different websites, local files or metadata tags to get the `LYRICS 🎵`
16. Enjoy!

## CREDITS

- <a href="https://github.com/RevenantX" target="_blank">RevenantX</a> CUE Fixer
- <a href="https://github.com/MordredKLB" target="_blank">MordredKLB</a> Enhanced Playback Statistics, MusicBrainz Tagger
- <a href="https://github.com/marc2k3" target="_blank">marc2k3</a> original foo_jscript_panel, Last.fm Playcount Sync
- <a href="https://hydrogenaudio.org/index.php/topic,124571.0.html" target="_blank">razielanarki</a> On-Screen Display
- <a href="https://github.com/jacquesh" target="_blank">Jacques Heunis</a> OpenLyrics
- <a href="http://www.byalexv.co.uk/" target="_blank">Alex Vallat</a> AlbumArtDownloaderXUI
- <a href="https://github.com/gix" target="_blank">gix</a> foo_scrobble
- <a href="https://github.com/foosion" target="_blank">foosion</a> Shorten decoder
- <a href="https://github.com/Yirkha" target="_blank">Yirkha</a> SHPECK
- <a href="https://www.geisswerks.com/" target="_blank">Ryan Geiss</a> Original MilkDrop author and curator of `favorite_presets_2021_01_03`
- <a href="https://github.com/TheQwertiest" target="_blank">TheQwertiest</a> Spider Monkey Panel, which powers most of this theme foo_spider_monkey_panel
- <a href="https://hydrogenaud.io/index.php?action=profile;u=322" target="_blank">Case</a> Waveform Minibar (mod), TAK Decoder, Taskbar Playback Progress Bar, TTA Audio Decoder  
- <a href="https://github.com/WilB" target="_blank">WilB</a> Library Tree Panel, Biography Panel
- <a href="https://www.patreon.com/posts/pack-nestdrop-91682111" target="_blank">ISOSCELES</a> MilkDrop 2 Preset Packs
- <a href="https://forums.winamp.com/forum/visualizations/milkdrop/milkdrop-presets/309644-waltra-milkdrop-preset-pack-77-presets" target="_blank">Waltra</a> MilkDrop 2 Preset Pack
