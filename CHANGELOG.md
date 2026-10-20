# What's new in V1.0.5

## New features

### A fresh Atlas installer

A compact new design with the original Atlas branding, clear version transitions and an animated blue-to-cyan progress bar. Used for both new installations and updates.

### A picture behind your accounts

Import a JPG or PNG from your PC or use drag and drop. Choose Fill or Fit, adjust darkening and enjoy a gentle introduction animation. Works with Atlas Glass and winter effects.

### Image intensity

Control picture visibility from Hidden (0%) to Full (100%) while preserving your Glass transparency. Darken image adjusts brightness separately.

### Optional snow pause

Enable Pause snowfall when Atlas is not focused (more performance) to freeze snowfall while using another app and resume from the same position when you return. Off by default.

### More winter companions

Hardcore now includes a snowman and a red-nosed reindeer face alongside candy canes and gingerbread figures.

## Performance

### Smoother window resizing

Tiles keep gliding smoothly into their new rows while Atlas skips redundant layout work and reuses their display order. Background images use faster scaling during the drag and return to their original quality afterwards. The image continues to follow the window size with your selected Fill or Fit mode.

### Static winter drawings are reused

Snow caps and decorations reuse prepared drawings. Snowfall resumes using its existing drawing layers, with the same detail and animation speed. Adding accounts does not add falling particles.

### One managed background image

Background images are optimised locally, loaded once and shared. Importing runs in the background without creating a separate image copy for every tile.

### Sliders follow your input

Image intensity, Transparency and Milkiness preview directly without repeatedly loading the image or restarting long colour transitions.

---

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

---

# V1.0.3

## Tags

- Create, edit, recolour, assign and delete multiple tags per account.
- Preview three compact tag cards per row; search and sort accounts by tag.
- Preserve tag colours across All accounts, My layout and groups.

## Editing and appearance

- Use the new rounded slider style throughout the app.
- Match Favorites, Templates and Tags buttons; round the Search table field.
- Keep tag editors and first-start patch notes opaque, without shadows.

## Updates

- Download and verify newer installers from the update indicator, then start setup.
- Show patch notes once after an upgrade, while leaving fresh installs clear.

---

# V1.0.2

## Fixes

- Remember window position, monitor and maximized state, with a visible fallback when a monitor is disconnected.
- Fit notes flyout columns without visible scrollbars; retain mouse-wheel access to longer content.
- Keep template colours, notices and notes consistent across All accounts, groups and My layout.
- Remove the dark background from clicked favorite stars on custom tile colours.
- Place Create Blank Tile before Cancel in Templates.

## Updates

- Check GitHub for a newer stable release on every startup, in the background.

---

# V1.0.1

## Templates

- Edit individual saved templates using the pencil button in the Templates overview.
- Change the template name, colours, notice, notes, group and blank table layout.
- Cancelling keeps the original template unchanged.

## Fixes

- Account tiles retain their own colours when rearranging My layout, with or without Atlas Glass.
- Drag indicators clear after dropping or cancelling a move.

---

# V1.0 Release

## Final fixes

- Popup windows now use a continuous native drag area across the title, subtitle and free header space. An inactive popup can activate and begin moving with the same mouse press; close buttons and editor controls retain their own interactions.
- Clean text on bright tile colours: removed the extra Glass outline throughout Atlas. Repeated appearance switches no longer retain an old caption or heading behind the current text.
- Close buttons turn red and rotate 90 degrees anticlockwise on hover, return smoothly on mouse leave and give a pressure animation when clicked. Editors keep their existing cancel behaviour.
- Installer layout adapts to Windows scaling. Labels, checkboxes and action buttons use their measured sizes; the window supports per-monitor DPI changes.
- New stable releases appear in a protected, nearly opaque update badge in the title bar before the window controls. It opens the specific GitHub release page.
- Visible naming is now **V1.0 Release**; the technical version remains **1.0.0**.

## Included improvements

- Independent screenshot columns, editable labels and compact screenshot icons.
- Removing a screenshot column and saving also removes its unused images; cancelling keeps stored images.
- Blank templates and blank layouts do not transfer private screenshots to other accounts.
- Clickable and draggable sliders, smaller table search and aligned editor controls.
- Templates can be deleted. Obsolete filters, Local data and Previous version controls are removed.
- Sharp Steam vector icon, aligned favorites and improved Glass sorting and colour transitions.
- Start and close screens retain their 1.5-second duration and status indicator.

## Windows message

See the [SmartScreen explanation in the README](README.md#windows-smartscreen).

