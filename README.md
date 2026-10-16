# Nintendo 64 RTA Web Emulator

A browser-based Nintendo 64 emulator front end with a simple, real-time controller input display.

**Live site:** https://frozican.github.io/Nintendo-64-RTA-Web-Emulator/

## Features

- Load a local N64 ROM file (`.z64`, `.n64`, or `.v64`)
- Runs through [EmulatorJS](https://emulatorjs.org/) using its N64 core
- On-page controller visualization for keyboard input
- Fullscreen mode
- Dark, responsive layout for desktop and mobile
- Emulator settings and toolbar controls are configured to be hidden
- Browser right-click context menu is disabled on the page

## How to use

1. Open the [live emulator website](https://frozican.github.io/Nintendo-64-RTA-Web-Emulator/).
2. Select **Choose ROM** and choose your own N64 ROM file.
3. Wait for the emulator to load. Initial startup may take a little while.
4. Use your keyboard to play. The page displays the keys it recognizes.

### Keyboard display mapping

| Keyboard key | Displayed control |
| --- | --- |
| Arrow keys | Analog stick |
| X | A |
| C | B |
| Z | Z trigger |
| Enter | Start |
| I / J / K / L | C buttons |
| Q / W | L / R |

The controller display is a visual aid. Its mapping may not exactly match EmulatorJS's active controller mapping in every browser or configuration.

## Important limitations

- This is an experimental RTA front end, not a frame-accurate TAS tool.
- It does not guarantee deterministic playback, frame stepping, or frame-perfect timing.
- Compatibility and performance depend on the browser, device, ROM, and EmulatorJS.
- The pause/restart controls may not behave like native emulator controls in every situation.
- EmulatorJS is loaded from its public CDN, so an internet connection is required.

## ROMs and legal note

No game ROMs are included or hosted by this project. Select only ROM files you are legally entitled to use. Nintendo 64 and game trademarks belong to their respective owners; this is an unofficial fan project.

## Development

The site is a static HTML page hosted with GitHub Pages. The emulator loader and supporting assets are provided by EmulatorJS.

Repository: https://github.com/Frozican/Nintendo-64-RTA-Web-Emulator
