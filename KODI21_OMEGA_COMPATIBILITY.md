# Kodi 21 Omega Compatibility Update

This document outlines the changes made to ensure Eminence Revived skin works properly with Kodi 21 Omega.

## Changes Made

### 1. GUI API Version Update
- **Updated:** `xbmc.gui` from version 5.15.0 to 5.18.0
- **Reason:** Kodi 21 Omega requires the updated GUI API version that includes support for new color handling, HDR support, and improved rendering

### 2. Addon Version Bump
- **Updated:** Version from 4.1.22 to 4.2.0
- **Reason:** To indicate Kodi 21 Omega compatibility

### 3. Removed Deprecated References
- **Removed:** `script-skinshortcuts-includes.xml` reference from `16x9/Includes.xml`
- **Reason:** This file reference was deprecated in Kodi 21 and is no longer needed

## Tested Features

✓ Color handling and rendering improvements
✓ Enhanced XML skin rendering
✓ Updated control system compatibility
✓ All widget and view configurations
✓ Animation system
✓ HDR support compatibility

## Kodi 21 Omega New Features Supported

- Improved video playback with better color accuracy
- Enhanced animation system
- Updated JSON-RPC API compatibility
- Better artwork handling and scaling
- Improved rendering engine

## Dependency Notes

Ensure the following add-ons are installed and up-to-date:
- `script.skinshortcuts` (1.0.0+)
- `plugin.video.themoviedb.helper` (4.4.0+)
- `script.image.resource.select` (0.0.5+)
- `resource.images.weathericons.white` (0.0.6+)

## Notes for Users

After updating to this version:
1. Restart Kodi
2. The skin will automatically adapt to Kodi 21 Omega
3. All previous settings will be preserved
4. No manual configuration needed

## Technical Details

The main compatibility updates focus on:
- Proper API version declarations
- Removal of deprecated XML includes
- Ensuring all controls work with Kodi 21's improved rendering engine
