YouTube-Extended: 18.31.40  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-3.2.0-all.jar  
Integrations: inotia00/revanced-integrations-0.117.12.apk  
Patches: inotia00/revanced-patches-2.190.12.jar  

YouTube
==
- fix(integration): apply more precise class names
- fix(integration): no longer override User-Agent when sending request
- fix(youtube/append-time-stamps-information): when the video quality is set to `Auto`, the quality is not displayed properly
- fix(youtube/hide-feed-flyout-panel): no longer overwrites default values https://github.com/inotia00/ReVanced_Extended/issues/1402
- fix(youtube/hide-info-cards): block new type of infocards https://github.com/inotia00/ReVanced_Extended/issues/1406
- fix(youtube/hide-suggestions-shelf): does not work on tablet https://github.com/inotia00/ReVanced_Extended/issues/1398
- fix(youtube/overlay-buttons): wrong formatted timestamps copied
- fix(youtube/settings): apply correct strings resource https://github.com/inotia00/ReVanced_Extended/issues/1392
- fix(youtube/settings): when rebooting from the AlertDialog displayed when first installed, reboot does not work properly
- fix(youtube/spoof-player-parameters): `Ambient mode`, `Clip`, `FilmStrip overlay`, `Thumbnail preview in SeekBar` does not working
- fix(youtube/spoof-player-parameters): remove dependencies that are no longer used
- feat(youtube/translations): update translation
`Arabic`, `Brazilian`, `Chinese Traditional`, `Greek`, `Korean`, `Russian`, `Spanish`, `Vietnamese`


YouTube Music
==
- feat(music): add support version `v6.20.51`
- feat(music): add `remember-repeat-state` patch
- feat(music): add `remember-shuffle-state` patch
- feat(music): remove `enable-force-shuffle` patch
- feat(music/hide-flyout-panel): add setting to hide podcast-related menus
- feat(music/litho-filter): no longer uses `identifier` parameter
- fix(music/exclusive-audio-playback): switch didn't actually work
- fix(music/import-export-settings): integrated into `settings` patch https://github.com/inotia00/ReVanced_Extended/issues/1391
- feat(music/translations): update translation
`Chinese Traditional`, `French`, `Greek`, `Indonesian`, `Korean`, `Polish`, `Russian`, `Spanish`, `Vietnamese`


Etc
==
- build: bump dependencies
- some side effects of the `spoof-player-parameter` patch have been fixed
- following known issues remain:
• Enhanced bitrate is not available
• Offline downloads may not work
• SeekBar thumbnail preview quality is very low


※ Compatible ReVanced Manager: [RVX Manager v1.9.7 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.9.7)
[Crowdin translation]
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
