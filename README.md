# DraftSense - free MTG Arena tracker and draft helper

**Website: [getdraftsense.com](https://getdraftsense.com)** · [Download](https://getdraftsense.com/download) · [Community stats](https://getdraftsense.com/community) · [FAQ](https://getdraftsense.com/faq) · [Discord](https://discord.gg/RJAycVPdg)

DraftSense (formerly **MTGA Tracker**) is a free companion for **Magic: The Gathering Arena**, for
Windows and macOS. The desktop app reads the log file Arena itself writes while you play:

- an in-game overlay with your deck list, draw odds and the action timer;
- a live draft board with card win rates and average pick from DraftSense players' games;
- match, deck, draft, sealed and reward history;
- game replays you can watch turn by turn and share with a link.

With a free account on [getdraftsense.com](https://getdraftsense.com) your games, drafts and decks are
also on the website: your stats, replays, [community win rates for every limited set](https://getdraftsense.com/community),
[tier lists](https://getdraftsense.com/tier-lists), [card pages](https://getdraftsense.com/cards),
leaderboards and groups to compare with friends.

This repository holds **downloads, release notes and bug reports**. The source code is private.

## Download

Get the latest version from [getdraftsense.com/download](https://getdraftsense.com/download) or the
[Releases page](https://github.com/zmac11/draftsense/releases/latest): a `.dmg` (or `.zip`) for macOS
and an installer `.exe` for Windows.

The installers are not code-signed yet, so the first time you open the app macOS or Windows shows a
warning. On macOS: right-click the app > Open. On Windows: "More info" > "Run anyway".

Before the first launch, turn on **Options > Account > Detailed Logs (Plugin Support)** in MTG Arena
and restart Arena once.

## Report a bug or suggest a feature

Open an [issue](https://github.com/zmac11/draftsense/issues/new/choose) or use
[getdraftsense.com/feedback](https://getdraftsense.com/feedback). Please include your app version
(tray menu) and what you were doing in Arena when it happened.

## Privacy

The app reads your local `Player.log` and Arena's local card database. Without an account nothing you
play leaves your computer. When you link the app to a DraftSense account, it uploads your games,
drafts, sealed pools, rank and collection to that account (you can switch uploading off in the app
and delete your data on the website). Community stats never name a player. Details:
[privacy notice](https://getdraftsense.com/privacy).

The app also contacts GitHub to check for new releases (can be turned off in Settings) and the
DraftSense website and Scryfall for card data, pictures and ratings.

## Wizards of the Coast

DraftSense is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by
Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC.

The app only reads files Arena writes on your computer. It never reads game memory, intercepts network
traffic or automates play.
