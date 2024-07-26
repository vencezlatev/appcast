# Changelog

All notable changes to this project will be documented in this file.

## [0.0.5] - 

Changed
- Force record start is now on start any change box as a additional option while waiting
- Expandable tile animation is now faster
- Delete all recordings is now in the menu bar as an option

Fixed
- Menu bar issues fixed
- Fixed bug with dmx value stop option
- Fixed progress indicator movement
- Before it was going to sent dmx without having a universe
- Will not show zones if there is only one in scene screen

Improved
- Improved switching between input and output
- Improved dmx value change option in advanced record
- Format duration can work with more than 99 minutes
- When something is changed it will show that the document has been edited
- Better error management
- Handle no space left in device
- Add recording instantly when duplicating
- Improved UI for license

Added
- Blocking mouse while reading or writing to the device
- Block open recording tile when while waiting to record
- Added scene settings
    - Loop Count
    - Stop at end
    - Fade in
- Added zone settings
- Added a patchIO
- Write show with patchIO on multiple devices
- Added way to reset universes options for only one device in write show screen
- Added TCA 
    - Conditions
        - Time 
        - Port
    - Actions (can add multiple actions in one TCA)
        - Scene
            - Start scene
            - Resume scene
            - Pause scene
            - Stop scene
            - Next scene
            - Previous scene
            - First scene
            - Last scene

## [0.0.4] - 17-06-2024

### Added

- Added a way to add all recordings to a XHL scene
- Added reset duration button for a recording in show scene
- Added snap position in edit screen
- Added force button to record
- Start on any change box is active by default 
- Able to change recording directories
- Retrieve last opened recording folder
- Show directory path when hover “Last records”
- Checking if there is something edited
- Asking user if he wants to save project before closing app, opening a new show or reading a show from device (with custom message for each edited part)
- Added option to read a show from device
- Able to create a new show
- Able to open a show
- Able to save a show
- Show files are now named .srep (Show recorder editor project)
- Recording files are now named .srer (Show recorder editor recording)
- Displaying the zones
- Added read/write patchio
- Added settings for scene (Loop count, Stop at end, Fade in)
- Added zone settings (set start scene)

### Fixed

- Artnet options fix
- Green current time in edit screen won’t appear if the position is at the beginning or the end
- Record assert fixed
- Loading “circles” will now keep state no matter on which screen is the user
- Don’t read corrupted files
- Show current time when quick replaying a recording not the full duration
- Processing only one recording conversation at a time into a xhl scene
- Fixed wrong values at end when dragging handles or indicator in edit screen

### Changed

- Right click to rename a recording from last recordings container
- New toast for messages
- Custom app bar MacOS
- Colors and behaviour changed in menu bar  for windows
- Circle progress indicator’s line endings are rounded
- Displaying toast information when changing records folder

### Improved

- Be able to replay only one show at a time
- Better performance while changing between Main and Show screen
- Improved error management for files
- Management for Input/output universes is improved
- Improved performance in edit screen
- Improved calculations for time and handles when resizing the screen 
- Improved Input sources resizable container
- Improved writing show to device

## [0.0.3] - 16-04-2024

[0.0.4]: https://github.com/Nicolaudie-UK/DMXRecorderFlutter/releases/tag/Alpha%2F0.0.4
[0.0.3]: https://github.com/Nicolaudie-UK/DMXRecorderFlutter/releases/tag/Alpha%2F0.0.3
