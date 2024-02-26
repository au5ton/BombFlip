---
layout: page
title: What's New
include_in_header: true
---

# Changelog
These are the past updates to Bomb Flip and their list of changes.

<br>

### `Latest`
# **Version 1.0.4**
Release Date: February 25, 2024

- Added links to the game's official soundtrack

Many thanks to the musician behind the soundtrack, socks.! If you enjoy the soundtrack, please consider supporting the creator.

# **Version 1.0.3**
Release Date: August 26, 2023

This update focuses on a bug where background audio from other apps wasn't being allowed to play while Bomb Flip was open.

In order for Bomb Flip to allow audio to be played from other apps, the "Background Music" volume must be turned completely off in the "Settings" page of the app.

This will be documented in the footer text of the "Background Music" section of the "Settings" page to make this new behavior more clear moving forward.

On another note, we've noticed a rise in new players lately. Thank you for playing Bomb Flip!

# **Version 1.0.2**
Release Date: July 13, 2023

This update focuses on bug fixes and quality-of-life changes that have come up since our last update.

#### What's New
- Added "Highest Level Reached" leaderboard
- New particle effects have been added throughout the app. Examples: when purchasing an item, and going up/down a level.

#### Quality-of-Life changes
- In the Settings, audio volume sliders now scale logarithmicly. This may mean that your audio settings will need to be adjusted to be more closely to what they previously where.
- Adjusted behavior when an entire row/column is memoed
- Item Shop "Buy" button is more accessible to users who play without audio, or are hard of hearing.
- Item Shop "Buy" button has been adjusted to prevent accidental purchases and to make it's actions more clear.
- GameCenter will now occassionally show "Highlights"

#### Bug Fixes
- Markdown text is rendered correctly in dark mode
- Smartphone item description updated reflect an already fixed bug
- Fixed bug where memoing a row/column didn't work if some of the tiles were already flipped
- Attempted to fix bug where the GameCenter access point would go missing
- Attempted to fix bug where a concurrency issue could cause sound effects within the app to be randomly loud

# **Version 1.0.1**
Release Date: July 6, 2023

This update focuses on bug fixes and quality-of-life changes that have come up since our last update.

#### What's New
- Added different links to give Feedback within the app
  - Links to: `Rate the App`, `Report a Bug`, `Suggest New Changes`, and to `Discuss on Discord`

#### Quality-of-Life changes
- Bomb Scanner algorithm tweaked to be more helpful and to (virtually) never fail (Issue #163 and #171)
- When an entire row/column is tapped to be memoed, and the row/column is already partially memoed, only update the un-memoed tiles (Issue #174)
- iCloud Sync indicator removed from the Game View to prevent confusion (Issue #177)

#### Bug Fixes
- Fixed issue where there's no way to close the Item Shop sheet on Apple Silicon Macs (Issue #176)
- Removed outdated warning when backing out of a Game and going to the Main Menu (Issue #173)

<br>

### `Initial Release`
# **Version 1.0**
Release Date: July 3, 2023

This is the initial App Store release of Bomb Flip.

<br>