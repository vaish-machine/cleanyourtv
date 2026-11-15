# NEXUS — Sony BRAVIA Android TV launcher

A customized Android TV home screen based on the CleanYourTV project.

## Tested device

- Sony BRAVIA 4K GB
- Android TV 9
- Physical TV testing with the Sony remote
- 1920 × 1080 screenshots captured using ADB

## Features

- Full-screen hero with time, date and TV controls
- D-pad navigation between the hero and application grid
- Highlighted application focus with contextual backgrounds
- Installed application launching and TV shortcuts

## Network behavior

This NEXUS source version does not request the Android INTERNET
permission. The previous YouTubeFeedCache and YouTubeFeedJob
components are absent from this source snapshot.

The installed apps launched from NEXUS, such as YouTube, may
independently access the Internet.

## Build

This folder contains the Android Gradle project source.
Use a compatible JDK, Android SDK and Gradle installation.
Consult the Gradle build configuration for required versions.

## Screenshots

[Hero screenshot](../docs/nexus/nexus-hero.png)

[Remote grid-focus screenshot](../docs/nexus/nexus-grid-focus.png)

## Attribution

Based on the CleanYourTV project. Preserve the original
upstream license and applicable dependency acknowledgements.