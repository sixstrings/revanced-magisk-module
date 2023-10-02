YouTube-Extended: 18.33.40  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-3.2.0-all.jar  
Integrations: inotia00/revanced-integrations-0.117.18.apk  
Patches: inotia00/revanced-patches-2.190.18.jar  

YouTube
==
- feat(youtube): add support version `v18.33.40`
- feat(youtube/custom-speed-overlay): change patch name `hide-speed-overlay` → `custom-speed-overlay`
- feat(youtube/custom-speed-overlay): editable speed value that changes while holding down (a/b tests)
- feat(youtube/spoof-app-version): change some target versions
- feat(youtube/spoof-player-parameters): update Known Issue https://github.com/inotia00/ReVanced_Extended/issues/1451
- fix(youtube/hide-button-container): `Hide like button` and `Hide dislike button` are not integrated https://github.com/inotia00/ReVanced_Extended/issues/1454
- fix(youtube/hide-endscreen-cards): wrong method name
- fix(youtube/hide-layout-components): wrong description - `Hide notify me button` https://github.com/inotia00/ReVanced_Extended/issues/1436
- fix(youtube/hide-mix-playlists): when MixPlaylists are included in my playlist (library), all playlists are hidden
- fix(youtube/navbar-index-hook): match to PR branch
- fix(youtube/settings): new layout does not load normally when rebooted through the reboot dialog that is shown when first installed
- fix(youtube/settings): remove unused code
- fix(youtube/settings): some patch descriptions and settings are not properly labeled https://github.com/inotia00/ReVanced_Extended/issues/1407
- fix(youtube/spoof-player-parameters): fix some bugs https://github.com/inotia00/ReVanced_Extended/issues/1437 https://github.com/inotia00/ReVanced_Extended/issues/1444 https://github.com/inotia00/ReVanced_Extended/issues/1449 
- feat(youtube/translations): update translation
`Arabic`, `Bengali`, `Chinese Traditional`, `French`, `Greek`, `Hungarian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- fix(music/enable-playback-speed): excluding enable playback speed patch still shows playback speed icon in the flyout menu https://github.com/inotia00/ReVanced_Extended/issues/1458
- fix(music/hook-download-button): change the URL format used when launching external downloads https://github.com/inotia00/ReVanced_Extended/issues/1460
- feat(music/translations): update translation
`Brazilian`, `Dutch`, `Greek`, `Italian`, `Korean`, `Polish`, `Russian`


※ Compatible ReVanced Manager: [RVX Manager v1.10.3 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.10.3)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
