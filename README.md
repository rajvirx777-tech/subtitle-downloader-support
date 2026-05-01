# Subtitle Downloader

Subtitle Downloader is an Android app for finding and downloading subtitle files for movies and TV episodes.

The app is built for local storage, SD cards, and network shares. You can browse to a video file, search for matching subtitles from multiple providers, and save the subtitle with the exact same filename as the video so your media player can detect it automatically.

## What the app does

- Search for movies and TV shows directly from the home screen
- Browse internal storage, external storage, and network locations
- Download subtitles and save them next to your video file
- Create subtitle files with the same base filename as the selected video
- Use multiple subtitle sources such as OpenSubtitles, SubDL, and Addic7ed (Addicted)
- Configure preferred subtitle languages and enabled providers
- Save favorite folders for faster navigation
- Create multiple profiles for different network locations or setups
- Bulk download subtitles for multiple episodes at once

## How it works

### 1. Search from the home screen

You can start from the home screen search bar to look up a movie or TV show.

This is useful when you want to quickly jump to matching media results without browsing through folders first.

From the home screen, you can also open the quick settings/search settings and choose the subtitle download location. That selected location is stored as the default download folder, so the app can keep using it for future downloads from the home screen.

For example, if you set the download location to a folder such as `Movies` on your internal storage, subtitles downloaded from the home screen will be saved there by default. On newer Android versions this default location is typically based on the internal `Movies` folder, while older Android versions may use the `Downloads` folder instead.

### 2. Browse to your video file

You can also use the built-in explorer to navigate through:

- Internal storage
- External/SD card storage
- Network drives and remote folders

If you use a NAS or shared folder, you can configure network access and explore those locations directly from the app.

### 3. Select a file and download a subtitle

When you select a video file, the app searches subtitle providers for matching results.

After you choose a subtitle, the app creates and saves the subtitle file using the exact same filename as the video file, in the same folder. This makes it easy for media players such as VLC, Kodi, or TV apps to detect the subtitle automatically.

Example:

- Video: `My.Show.S01E01.mkv`
- Subtitle: `My.Show.S01E01.srt`

### 4. Save to local storage or a network drive

The app can save subtitle files not only to local folders, but also to configured network locations.

This is useful if your media library lives on a NAS, shared SMB folder, or SFTP location and you want subtitles to be written directly to the remote folder.

If you are downloading from the home screen instead of selecting a specific video file first, the app uses the default download location from the quick settings. This makes it easy to always save subtitles to the same folder on internal storage, external storage, or a network location.

## Subtitle sources

Subtitle Downloader can search across multiple providers, including:

- OpenSubtitles
- SubDL
- Addic7ed (Addicted)

Depending on the app version and Android version, the list of enabled providers may vary. You can manage providers in the download settings.

## Profiles

The app supports multiple profiles.

Profiles are useful when you have different setups, for example:

- One profile for your home NAS
- One profile for a different network share
- One profile for local-only browsing

You can create and switch profiles from the hamburger menu on the left side of the app. This makes it easier to maintain different favorite folders, network configurations, and preferences for different environments.

## Network support

The app supports browsing and saving through network connections. This allows you to work directly with media stored outside your phone or tablet.

Typical use cases include:

- Exploring a shared movie folder on your NAS
- Opening a TV show folder on a remote server
- Saving downloaded subtitles directly to the network location

## Bulk downloading

If you want to download subtitles for multiple episodes of the same show, you can use the bulk selection feature:

1. Open the folder that contains the episodes
2. Long press one file to start selection mode
3. Select multiple files from the same show
4. Tap the search icon in the bulk actions bar
5. Download subtitles for the selected items

This is especially useful for season folders where you want to subtitle several episodes in one go.

## Settings overview

The app includes settings for:

- System settings
- Download settings
- Network settings
- Backup and restore

From these sections you can manage profiles, subtitle languages, providers, OpenSubtitles credentials, network folders, and backups.

## Support and help

The support section in the app can point users to:

- The changelog
- The in-app help center / FAQ
- The GitHub issues page for bugs and feature requests
- This repository home page/manual

## Notes

- An OpenSubtitles account may be recommended or required for higher download limits
- Available providers and capabilities can depend on the Android version and current app configuration
- Favorite folders and profiles can help speed up daily use when working with recurring local or network locations

## Issue tracker

Report bugs or request features here:

https://github.com/giejay/subtitle-downloader-support/issues

## Repository home page

Project/manual home page:

https://github.com/giejay/subtitle-downloader-support
