<p align="center">
  <img src="https://avatars.githubusercontent.com/u/347276872?s=200&v=4" width="100" height="100" alt="LMOxide logo">
</p>

<h1 align="center">LMOxide</h1>

<p align="center">
    LEGO Minifigures Online (LMO) written in Rust (Iron Oxide)
</p>

<p align="center">
  <a href="https://lmoxide.github.io/"><b>Website</b></a> ·
  <a href="https://github.com/LMOxide/lmoxide-patcher/releases/latest"><b>Download the patcher</b></a> ·
  <a href="https://github.com/LMOxide/lmoxide/blob/main/docs/HOSTING.md"><b>Host a server</b></a>
</p>

A server for LEGO Minifigures Online, which Funcom shut down in 2016. The last released client
works again on Windows and Linux: the worlds and dungeons, combat, the minifigure collection,
loot, achievements, quests, friends, teams and multiplayer. Everything was reverse-engineered
from the client; no game files are distributed.

**Play:** download the [patcher](https://github.com/LMOxide/lmoxide-patcher/releases/latest)
(Windows, Linux, macOS), enter a server's address, and it installs the client, keeps it up to
date and starts the game.

**Host:** one Docker Compose file runs the server, the web UI, the dev UI and the Discord bot
from published images ([HOSTING.md](https://github.com/LMOxide/lmoxide/blob/main/docs/HOSTING.md)).

| Repository | |
|---|---|
| [lmoxide](https://github.com/LMOxide/lmoxide) | the game server, REST API, patch server and command-line patcher (Rust) |
| [lmoxide-content](https://github.com/LMOxide/lmoxide-content) | the game's data: worlds, NPCs, skills, loot, minifigures, achievements, quests |
| [lmoxide-patcher](https://github.com/LMOxide/lmoxide-patcher) | the desktop patcher and launcher for players |
| [lmoxide-webui](https://github.com/LMOxide/lmoxide-webui) | the web UI: accounts, characters, moderation |
| [lmoxide-dev-ui](https://github.com/LMOxide/lmoxide-dev-ui) | the debugger and the world editor for testers and contributors |
| [lmoxide-discord-bot](https://github.com/LMOxide/lmoxide-discord-bot) | registration, roles and moderation from Discord |
| [lmoxide.github.io](https://github.com/LMOxide/lmoxide.github.io) | the website |

<sub>A fan project, not affiliated with or endorsed by the LEGO Group or Funcom. LEGO and LEGO
Minifigures are trademarks of the LEGO Group.</sub>
