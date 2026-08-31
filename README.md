# Lumina 0.15.6

Scripture presentation for Windows and macOS. This repository holds the installers
and the update manifest only — the source code is private.

Lumina updates itself: **Settings → Updates → Check now**. The downloads below are
for a first install, or for a machine you would rather update by hand.

## Download

- **Windows** — [Lumina_0.15.6_x64-setup.exe](https://raw.githubusercontent.com/andreigerman01-ai/lumina-releases/main/Lumina_0.15.6_x64-setup.exe)
- Windows, MSI installer — [Lumina_0.15.6_x64_en-US.msi](https://raw.githubusercontent.com/andreigerman01-ai/lumina-releases/main/Lumina_0.15.6_x64_en-US.msi)
- **macOS**, Apple Silicon and Intel — [Lumina_0.15.6_universal.dmg](https://raw.githubusercontent.com/andreigerman01-ai/lumina-releases/main/Lumina_0.15.6_universal.dmg)

The builds are not signed with a paid developer certificate yet, so the first open
needs a nudge: on macOS right-click the app and choose Open, and on Windows choose
"More info" then "Run anyway". Updates installed from inside Lumina are verified
against its own signing key instead, and a download that does not match is refused.

## What changed in 0.15.6

The Berean Standard Bible is available to install. Open Settings → Translations and it is listed alongside the Cornilescu; it is a modern English translation, dedicated to the public domain in 2023, and about 4 MB to download.

It is also the first text Lumina carries that does not number its verses straight through. The Berean is translated from the older manuscripts and so leaves out a handful of verses the King James carries — there is no Matthew 17:21 and no John 5:4, for instance. Two things went wrong with that:

- Pressing Next on the verse before one of the gaps put an empty slide on the screen, and pressing Next again carried on as normal. The verse arrows now step straight over a gap in either direction.
- Typing a reference to a verse a translation does not have showed nothing at all. It now opens the next verse that exists.

Neither affected the King James or the Cornilescu, which number every verse consecutively.

## Files

- `Lumina_0.15.6_universal.app.tar.gz` — 7.4 MB
- `Lumina_0.15.6_universal.dmg` — 7.7 MB
- `Lumina_0.15.6_x64-setup.exe` — 3.0 MB
- `Lumina_0.15.6_x64_en-US.msi` — 4.0 MB
