<p align="center">
  <img src="assets/banner.png" alt="Jarvis, a Dota 2 assistant: the voice in your ear that keeps count of the game" width="100%">
</p>

<p align="center">
  <b>Stop counting. Start playing.</b><br>
  Jarvis tracks the timers, cooldowns and builds you keep forgetting, and tells you in time to act on them.<br>
  Free. Windows. No account.
</p>

> [!NOTE]
> **Jarvis is in beta.** Things will break, and some features are still being tuned on real games.
> The interface and voice are in Ukrainian for now; an English version is next.
>
> **Tell us what you think.** What should be better? What is missing? What should go? [Open an issue](../../issues): every idea helps.

<p align="center">
  <img src="assets/in-game.jpg" alt="Jarvis's layers over a Dota 2 match: ultimate cooldowns and buybacks under the portraits, a spoken line under the clock, timers on the left, last-seen marks on the minimap, the next item on the right" width="100%">
  <br>
  <sub>Jarvis's real layers from a replay of a real match, placed over a screenshot of that same match, because they are hidden from screen capture. The ultimate cooldowns and buybacks under the portraits and the spoken line are samples. Names on screen are blurred.</sub>
</p>

## What it does

### In the match

| | |
|---|---|
| **A voice in your ear** | Runes, Roshan, Tormentor, stacks, lotuses, wisdom shrines, glyphs of both teams, enemy buybacks, outposts. Said about 15 seconds before they matter. You keep your eyes on the fight. |
| **Enemy ultimates, by ear** | Jarvis knows the sound of more than 90 ultimates. When one goes off near you, its cooldown starts under that hero's portrait, and you hear when it is ready again. *Beta: still being tuned, because the game often plays these sounds quietly.* |
| **Key items, by ear** | Black King Bar, Aeon Disk, Linken's Sphere, Refresher, Lotus Orb. It tells you when an enemy's BKB runs out and warns you when someone near you goes invisible. |
| **Who is missing** | An enemy gone from your minimap for 10 seconds gets called out and marked where you last saw him, with a timer. Killed heroes and destroyed wards are left out. |
| **What to level, what to buy** | A frame on the skill worth leveling, right on Dota's own button. The next item, from games at your own rank or from pro games, and what answers this enemy line-up. |
| **Which neutral item to craft** | Frames on the crafting panel: what pros take on your hero at this tier. |

### Before and after

| | |
|---|---|
| **Draft help** | The three best picks framed on Dota's hero grid, each with a reason you can read: which enemy it beats and why. Hero statistics at your rank, never information about players. |
| **The post-game show** | A full-screen report: your MMR change, the team's MVP and its biggest letdown, what every player did well and badly, with praise and roasts to match. |
| **Your last 30 days** | Your best and worst heroes, when you win and when you don't, and the one habit costing you the most games. |

## Built to play fair

Jarvis works only with what Valve provides and what is already on your screen.

**What it uses**

- **Game State Integration**, the official data feed Valve built into Dota 2
- **Public match statistics** from OpenDota and, if you choose, STRATZ
- **The picture on your own screen and the sound of your own PC**, the same way a streaming app captures them
- **Its own windows** on top of the game

**What it never does**

- Reads the game's memory or injects anything into it
- Changes game files
- Presses a key, clicks or buys anything for you
- Shows you anything the game hides: fog stays fog
- Looks up the other players before or during the draft

**The honest part.** Valve does not certify third-party apps, so nobody can truthfully promise you zero risk. Jarvis stays away from what Valve has banned accounts for: reading data from the game client and scouting players in the draft. Valve has not said anything specific about reading hero portraits off the screen in the draft, so you can turn that off in the settings.

## Your data stays yours

- **No account and no keys.** Jarvis ships with no API keys and works without any.
- **Optional STRATZ token.** To get item advice from your own rank, you can paste your own free token. Windows encrypts it on your PC, and it is only ever sent to STRATZ.
- **No telemetry and no server of ours.** Recordings, reports and settings stay on your computer. Jarvis only talks to Valve's image servers for hero icons, to OpenDota with your public account ID, and to STRATZ if you connected it.

## Getting started

**Download:** the first public build is coming to [Releases](../../releases).

1. Run the installer. The app is not code-signed yet, so Windows may warn you: choose **More info**, then **Run anyway**.
2. In Steam, open Dota 2's **Properties** and add `-gamestateintegration` to the launch options.
3. Set Dota's display mode to **Borderless window**, so Jarvis can draw over the game. In exclusive full screen you still get the voice.
4. Play. Jarvis connects by itself.

Tested on Windows 11. You can turn every cue and hint on or off, and resize the cards.

## About this repository

This page and the ready-to-install builds live here. The source code is closed.

---

<sub>Jarvis is an independent fan project. It is not affiliated with or endorsed by Valve. Dota 2 is a trademark of Valve Corporation.</sub>
