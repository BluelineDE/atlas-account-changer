# What's new in V1.0.4

## New features

### See your active Steam account

A subtle animated outline marks the account currently signed in to Steam. During a switch, two soft lights travel along its lower edge until the new account is confirmed. Works in All accounts, My layout and groups.

### RGB outline

Choose Automatic contrast, Custom colour or RGB in Settings → Outline. Adjust light trail speed and RGB colour speed separately. Changes preview live and save with Apply.

### A little winter atmosphere

Choose Off, Light or Hardcore in Settings → Winter effects. Hardcore adds snow across the tiles, candy canes and gingerbread figures. Decorations are random each start and follow moved tiles. Set snow fall speed from 0.25× to 2.50×. Works with Glass and solid backgrounds; off by default.

### Settings, easier to find

Four pages organise your settings: Overlay, Outline, Winter effects and General. Changes preview live; Apply saves them and Cancel restores your previous choices.

### Atlas on Discord

Enabled by default: Atlas logo, Organising accounts, elapsed time and a Website button. Account names, login names, Steam IDs, groups, tags and notes stay private. Discord must be running with activity sharing enabled. Turn it off in Settings → General.

### Support Atlas

The optional Support Atlas button in Settings → General opens the project's PayPal donation page in your browser.

### Delete several tags or templates

Use the trash button beside Create tag or Create Blank Tile to select several items. Confirm once to delete them together, or choose Cancel selection to keep everything.

## Performance

### A smoother first visit to My layout

Atlas prepares group tiles in small steps after startup. The first visit can reuse them while keeping your current page, scroll position and saved layout. Search, account changes and navigation stay up to date.

### More efficient grouping and snowfall

Group membership and ordering are processed more efficiently. Snowfall shares animation layers and keeps the same number of flakes as your account library grows, with fewer ongoing memory allocations. Minimizing pauses animations and preparation.

## Bug fixes & improvements

### Stable outlines and winter decoration

The old account stays marked until Steam confirms the replacement, then the outline fades across. The moving light is always white. Snow covers the full tile width and its upper outline. Decorations move with their tiles and never block clicks. Snow resumes from its previous position after pausing or minimizing.

### Tags and templates, easier to clean up

Deleted tags disappear from all account tiles. Deleting a template removes its unchanged applied settings and restores previous values. Later manual changes are kept. Identifiable matching older tiles are also cleaned up; private table values are retained.

### More room for templates

Two complete rows fit without a scrollbar. Scrolling starts with the third row. Previews adjust to the available space and keep their actions visible. Selection and removal use smooth transitions.

### Sharper text and consistent controls

Account text is clearer at different display scales. Sliders share rounded handles and support clicking or dragging. Automatic contrast clearly disables and greys out custom colour controls.

### Compact project information

Settings → General places the version beside a small Info button. Support Atlas uses a compact button with its explanation below it. Both keep the familiar rounded style and hover transitions. Settings remains solid with Glass enabled.

### A clearer notice menu

The tile menu says Add important notice. Apply Important Notice to Multiple Tiles appears only when the source tile has a notice. The account-switch counter has also been removed from Discord activity.

### Your existing setup stays yours

Accounts, groups, tags, templates, colours, notes and window position are retained. This solid news window appears once after an update. OK or X dismisses it for this version; a fresh installation does not open update news.

## Install

Download **Atlas_Account_Changer_V1.0.4_Setup.exe** below. Close Atlas before running setup. Existing accounts and settings are retained. The Windows runtime is included.

V1.0.3 users can click the update notice to download and install this release. Earlier versions open GitHub; download the current installer from this page.

Update news appear once on the first start after upgrading. A fresh installation does not open update news.

## Windows SmartScreen

This installer is unsigned. Windows may display “Windows protected your PC” or “Unknown publisher”; the publisher is not verified through a trusted code-signing certificate. Download Atlas from this official project.
