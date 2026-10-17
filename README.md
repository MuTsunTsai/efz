# ETERNAL FIGHTER ZERO Web

**English** | [正體中文](README.zh-TW.md) | [日本語](README.ja.md)

An unofficial port of ETERNAL FIGHTER ZERO that runs in your web browser.

**This program does not include any game data.** To play, you need your own copy of the ETERNAL FIGHTER ZERO **version 4.02** game folder.

## Getting Started

1. Open the web page, press "Select game folder" and choose the EFZ game folder that contains `efz.exe` and the `system` folder. You can also drag the folder onto the page.
2. After the first time, the game files are kept in this browser. Next time, just open the page and press "Start game"; there is no need to select the folder again.
3. Once the game has been loaded, you can also play offline.
4. You can also install it as a standalone app using your browser's "Install app" or "Add to Home screen" option.

To remove the game files stored in your browser, press "Clear stored game data" on the start page.

The page is shown in English, Traditional Chinese or Japanese automatically, based on your browser's language settings.

### Notes

- Use an up-to-date desktop browser such as Chrome, Edge or Firefox.
- Only game data from version 4.02 is supported. Files from any other version may cause unexpected behavior.
- The browser cannot write back to your game folder, so in-game settings, records and newly recorded replays are stored only in this browser and your original files are never modified. Clearing the browser's site data also deletes them.
- If the folder contains a `key.ini`, its key settings are used.
- The game logic of this port follows the original version 4.02. It does not include the changes EFZ Revival makes to the game (such as the priority of simultaneous left and right inputs, the initialization of some variables, and forcing the effects setting).
- Replays recorded with EFZ Revival can be played back, but because Revival applies the changes above while recording, playback may differ from the match as it was actually played. The same happens when playing them in the original game without Revival.

## Controls

### Default Keys

| | Up | Down | Left | Right | Light | Medium | Heavy | Sp |
|---|---|---|---|---|---|---|---|---|
| 1P | Y | N | G | J | Q | W | E | D |
| 2P | ↑ | ↓ | ← | → | P | [ | ] | \ |

- In the original game, 2P's Medium / Heavy / Sp are the three keys to the right of P on a Japanese keyboard. On a US-layout keyboard they map to `[` `]` `\`.
- Gamepads (up to two) are supported, mapped according to the gamepad settings in `key.ini`.
- ESC: goes back to the previous screen; on the title screen it quits the game and returns to the start page.

### Touch Devices (Phones and Tablets)

- The game switches to full screen when it starts, and the layout follows the device orientation.
- If "Show on-screen controller" is checked on the start page (the choice is remembered), a semi-transparent controller appears: a directional pad at the bottom left, and four buttons on the right (right: Light, up: Medium, left: Heavy, down: Sp), plus an ESC button at the top left.
- The on-screen controller always controls 1P, regardless of the key settings in `key.ini`.
- During a match, buttons for the function keys available in the current mode appear at the top right (for example, F8 Pause in every mode, plus F4–F7 in Practice mode). They work the same as the function keys below.

### Function Keys

| Key | Action | When |
|---|---|---|
| F1 | Reload the key settings from `key.ini` | Any time |
| F2–F4 | Switch to key setting set 1–3 in `key.ini` | Any time (when `key.ini` has them) |
| F4 (hold) | Adjust the gauge | During a match (modes other than Arcade) |
| F5 | Cycle test values for gauge and life | During a match (modes other than Arcade) |
| F6 | Cycle the CPU's stance (standing / jumping / crouching) | Practice mode |
| F6 | Restart recording | While recording in Replay mode |
| F7 | Toggle the CPU's auto guard | Practice mode |
| F8 | Pause | During a match |

- The browser's F5 (reload) is disabled; press Ctrl+R to reload the page.
- F11 (full screen) and F12 keep their usual browser functions.

## Privacy

- The game files you select are read and processed only in your browser and are never uploaded or transmitted to any server.
- This website uses Google Analytics to measure visits (general information such as page views, browser and region). This data is handled according to Google's privacy policy. Google Analytics never receives your game files.

## Legal Notice

- This is an unofficial, independent port. It is not affiliated with, endorsed by, or sponsored by the developer or publisher of the original game, or by the rights holders of the original characters.
- ETERNAL FIGHTER ZERO was created by Tasogare Frontier. Its characters originate from works including ONE \~Kagayaku Kisetsu e\~, Kanon and AIR. All game titles, characters, artwork, music, sound effects and other original materials remain the property of their respective owners.
- This project does not include or distribute the original executable or any game data. Users must provide their own game files and are responsible for ensuring that their use of those files is lawful. This project does not grant any license or other rights to the original game, its assets, or any third-party intellectual property.
- This program supports only the game data of ETERNAL FIGHTER ZERO version 4.02. Using files from any other version may cause unexpected behavior.
- Game files selected by the user are read and processed locally in the browser and are never uploaded or transmitted to any server. So that the folder does not have to be selected again, the files are kept in the browser's local storage and can be deleted at any time from the start page. Game settings and records are likewise stored only in the browser.
- This website uses Google Analytics to measure visits. Game files are never sent to Google Analytics.
- This software is provided "as is", without warranties of any kind, to the extent permitted by applicable law.

See [LICENSE.md](LICENSE.md) for the license terms.
