#### ⚠️ Do not download modules from 3rd party sources like random websites you found on Google. There are many that use these modules and impersonate ReVanced and ReVanced Extended.



Extensive ReVanced Extended (RVX) and ReVanced builder.


[![Github All Releases](https://img.shields.io/github/downloads/sixstrings/revanced-extended-magisk-module/total.svg)]()

Get the [latest CI release](https://github.com/sixstrings/revanced-extended-magisk-module).

[**mindetach module**](https://github.com/sixstrings/mindetach-magisk)
in the releases section detaches YouTube and YouTube Music from Play Store and blocks their forced updates.

## Features
 * Support all present and future ReVanced and [ReVanced Extended](https://github.com/inotia00/revanced-patches) apps
 * Can build Magisk modules and non-root APKs
 * Updated with the latest versions of apps and patches
 * Optimize APKs and modules for size
 * Modules
     * recompile invalidated odex for faster usage
     * receive updates from Magisk app
     * do not break safetynet or trigger root detections
     * handle installation of the correct version of the stock app and all that
     * support Magisk and KernelSU



## To include/exclude patches or patch more ReVanced Apps
[**See the list of patches**](https://j-hc.github.io/rvmm-config-gen/)

 * Star the repo :eyes:
 * [Fork the repo](https://github.com/j-hc/revanced-magisk-module/fork) or use it as a template
 * Customize [`config.toml`](./config.toml) using [rvmm-config-gen](https://j-hc.github.io/rvmm-config-gen/)
 * Run the build [workflow](../../actions/workflows/build.yml)
 * Grab your modules and APKs from [releases](../../releases)

also see here [`CONFIG.md`](./CONFIG.md)

# Building Locally
## On Termux
```console
bash <(curl -sSf https://raw.githubusercontent.com/j-hc/revanced-magisk-module/main/build-termux.sh)
```

## On Desktop
```console
$ git clone --recurse https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh
```
