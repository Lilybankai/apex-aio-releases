# Apex AIO System — releases

Downloads for **Apex AIO System**, the overlay and race-engineer app for
Le Mans Ultimate by [Apex & Chill Racing](https://apexandchillracing.co.uk).

**[⬇ Download the latest version](https://github.com/Lilybankai/apex-aio-releases/releases/latest)**

This repository holds nothing but the installers. It is where the app's own
auto-updater looks, and where the download link on the site points. The source
code lives elsewhere and is not public.

## What each release contains

| File | What it is |
|---|---|
| `Apex-AIO-System-Setup-<version>.exe` | The installer. This is the one to download. |
| `Apex-AIO-System-Setup-<version>.exe.blockmap` | Lets the updater download only the parts that changed. |
| `latest.yml` | The update manifest the installed app reads. Not for humans. |

Every installer is signed by **The Lilybank Agency Ltd** — Windows will show
that name rather than "unknown publisher".

## Stable and beta

Releases marked **Pre-release** are beta builds, and installed copies only see
them if the driver has switched to the beta channel in **Settings → Updates**.
A plain release goes to everyone. The channel is decided by the version number:
`0.99.3` is stable, `0.99.3-beta.1` is beta.

## Installing

Download the `.exe` and run it. The app updates itself after that — it checks
on launch and every few hours, and tells you when there is something new.

## Changelog

`CHANGELOG.md` in this repository carries the notes for every version, and the
same notes appear on each release below.

## Something wrong?

Report it in the Apex & Chill Discord, or through **Suggestions** in the app
itself.
