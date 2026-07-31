# windhawk-assets

Images referenced by the readme blocks of my [Windhawk](https://windhawk.net/) mods.

**Please do not delete this repository, and do not rename or move files inside it.**

Windhawk mod readmes may only embed images from `i.imgur.com` or
`raw.githubusercontent.com`, and the readme ships inside the mod's `.wh.cpp`
file in [ramensoftware/windhawk-mods](https://github.com/ramensoftware/windhawk-mods).
The mods catalog and the Windhawk client fetch these URLs live — there is no
cache. If a file here disappears, every user of the mod sees a broken image
until a new pull request is merged upstream.

## Layout

One folder per mod, named after the mod id:

```
<mod-id>/
  demo.gif
  settings.png
```

## Linking

Link the `main` branch so an image can be improved without touching the merged
mod file:

```
https://raw.githubusercontent.com/Deen-0x/windhawk-assets/main/<mod-id>/demo.gif
```

To replace an image, commit over the existing path — keep the filename stable.

## Before removing anything

1. Open a pull request against `ramensoftware/windhawk-mods` updating the
   affected readme URLs.
2. Wait for it to merge.
3. Only then delete or rename here.

Making this repository private has the same effect as deleting it.
