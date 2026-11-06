# Local Video Saver — Releases

Official release channel for Local Video Saver for Windows.

## Downloads

Download the latest published version from the [Releases](https://github.com/ruslepc-max/LocalVideoSaver-Releases/releases) page.

## Automatic updates

The desktop application checks this public repository for the latest GitHub Release:

`https://api.github.com/repos/ruslepc-max/LocalVideoSaver-Releases/releases/latest`

For automatic in-app updates, each stable release must include exactly one portable application ZIP asset named like:

`LocalVideoSaver_Portable_vX.Y.Z.zip`

The ZIP must contain the packaged `LocalVideoSaver/` directory, including `LocalVideoSaver.exe`, its runtime files, FFmpeg, Deno, and `updater.ps1`.

Do not upload source-code project archives as update assets. GitHub's automatically generated source ZIP and tarball are not application packages.

## Versioning

Use tags in the form `vMAJOR.MINOR.PATCH`, for example `v1.0.1`. Publish stable releases (not drafts or pre-releases) only after testing.

## Release notes

Describe user-visible changes, fixes, and known limitations in each release.
