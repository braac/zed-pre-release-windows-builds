# Unofficial pre-release builds of Zed for Windows

**NOTE: This is not a support channel for Zed on Windows.**

These builds are for those who want to experience the latest prereleases of Zed on Windows. 

Any issues with the Windows build should go through official channels, as this repository does not concern itself with the source code of Zed or issues found therein. 

If you have suggestions for improvements to the build process, please start a discussion or make a PR. 

## Installation

1. Extract the latest .zip from [Releases](https://github.com/braac/zed-windows-builds/releases)
2. Run the executable

### For Windows 10 users

Zed may not start unless you install the [Microsoft Visual C++ Redistributable 2022](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022) package. If you are using Scoop, you can install it using the following command:

```
scoop bucket add extras
scoop install vcredist2022
```

## Is it safe?

This repository contains a [simple GitHub workflow](./.github/workflows/build.yml) that builds a windows executable from Zed [pre-release](https://github.com/zed-industries/zed/releases?q=pre&expanded=true) source codes.

See the [Zed homepage](https://zed.dev/) or [official repository](https://github.com/zed-industries/zed) for more details.
