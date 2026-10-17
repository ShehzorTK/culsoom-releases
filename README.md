# CULsoom

Find any moment in a wedding gallery by describing it. CULsoom is a Mac app for photographers: add the edited photos from a shoot and it tags every moment, groups the people, writes a description of each photo, and lets you search in plain words, like "bride hugging her mother and crying" or "barefoot on the sand".

Everything runs on your Mac. No photo is sent to a cloud AI, and your original files are only ever read.

## Download

**[Download the latest version](https://github.com/ShehzorTK/culsoom-releases/releases/latest)** (the `.dmg` file under Assets). For Apple Silicon Macs (M1 or newer).

### Install

1. Open the `.dmg` and drag **CULsoom** into your Applications folder.
2. Open it. The first time, macOS says it can't verify the app, because it isn't signed with an Apple developer account yet. Right-click the app, choose **Open**, then **Open** again. If you don't see an Open button, go to System Settings, Privacy & Security, and choose **Open Anyway**.
3. On the first launch CULsoom sets up its photo engine. It needs the internet once and downloads about 2 GB. After that it works offline and starts in seconds.

## What you can do

- Add photos from folders on your Mac or from a WFolio gallery link. Name each event whatever you like.
- Get about 190 tags per shoot: places, light, style, clothing, details, actions, mood, and wedding moments.
- Tell it once who the bride, groom and parents are. Tags like "with bride" and "hugging mother" then follow them through every photo. Click any face to correct it.
- Search one shoot or all of them. Only photos that match are shown.
- Check the AI's guesses one photo at a time.
- Export organised copies with the tags written into each JPEG as Lightroom keywords, or a CSV or JSON tag list. Your originals are never changed.

## Good to know

- Your library is in `~/Library/Application Support/CULsoom`. Removing a shoot in the app deletes only the app's copies, never your photos.
- Photos are never cropped, and nothing leaves your computer.
- This is an early version. Mac only (Apple Silicon). Tags are tuned on a few galleries so far, so expect some misses; every tag can be corrected.

The source code is private.
