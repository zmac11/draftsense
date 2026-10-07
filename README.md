# DraftSense

DraftSense (formerly **MTGA Tracker**) is a free companion app for **Magic: The Gathering Arena**:
an in-game overlay with your deck list and draw odds, the action timer, draft help, and
match, deck, draft and reward history - all built from the log file Arena itself writes.

This repository holds **downloads, release notes and bug reports**. The source code is private.

## Download

Get the latest version from the [Releases page](https://github.com/zmac11/draftsense/releases/latest):
a `.dmg` (or `.zip`) for macOS and an installer `.exe` for Windows.

The installers are not code-signed yet, so the first time you open the app macOS or Windows shows a
warning. On macOS: right-click the app > Open. On Windows: "More info" > "Run anyway".

Before the first launch, turn on **Options > Account > Detailed Logs (Plugin Support)** in MTG Arena
and restart Arena once.

## Report a bug or suggest a feature

Open an [issue](https://github.com/zmac11/draftsense/issues/new/choose). Please include your app
version (tray menu) and what you were doing in Arena when it happened.

## Privacy

The app reads your local `Player.log` and Arena's local card database. It does not upload anything.
It contacts GitHub to check for new releases (can be turned off in Settings) and Scryfall for card
images and text.

## Wizards of the Coast

DraftSense is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by
Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC.

The app only reads files Arena writes on your computer. It never reads game memory, intercepts network
traffic or automates play.
