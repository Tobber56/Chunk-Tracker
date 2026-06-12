# Chunk Tracker
**Chunk Tracker** is a client-side Fabric mod for Minecraft 1.21.1 that automatically logs every block in each chunk you load and alerts you when watched blocks appear nearby.
> ⚠️ **This mod is still a work in progress.** Bugs are to be expected.

> Please visit my [GitHub page](https://github.com/Tobber56/Floonks-Mods) to see my other mods and for sending bug reports, suggestions, and questions.

> ⛔ **Server Warning** — Chunk Tracker can make it easier to locate other players bases and structures. Always check the server rules and get permission from staff before using it, and never use it to harass or grief other players.
---
## How It Works
Every chunk you load is automatically scanned and saved to a log file. You can search through your chunk history at any time and set waypoints to navigate back to specific blocks. If a watched block is found in a newly loaded chunk, you'll get an in-game sound alert.

---
## GUI
Open the GUI with `/chunktrack gui` or set a keybind in the settings menu.
### 🔍 Search Tab
Search your entire chunk history by block name. Results are sorted from closest to farthest and update live as new chunks are scanned. Click any row to place a waypoint on that chunk.
### 🔔 Alerts Tab
Shows every chunk where a watched block was found, sorted from closest to farthest. Updates in real time as you explore. Click any row to place a waypoint.
### 🗺️ Biomes Tab
Browse every biome found in your scanned chunks, sorted from closest to farthest. Click a row to highlight the biomes outer border in the world and set a waypoint to its center point.

---
## Alert List
Add blocks to your watchlist and get a sound alert the moment they appear in a loaded chunk.

---
## Commands
```
/chunktrack gui          — Open the Chunk Tracker GUI
/chunktrack list         — List all blocks in your current chunk
/chunktrack alert add    — Add a block to the alert watchlist
/chunktrack alert remove — Remove a block from the watchlist
/chunktrack alert list   — Show the current watchlist
```
---
## Notes
- **Client-side only** — works on any server, no server-side installation needed
- Chunk logs are saved in your Minecraft instance folder
