<div align="center">

# ⚔️ CrypTale

**Procedural dungeons for Hytale servers**

![Version](https://img.shields.io/github/v/release/OzL-Prod/CrypTale-releases?color=gold)
![Hytale](https://img.shields.io/badge/Hytale%20server-0.7.5%2B-blue)
![Java](https://img.shields.io/badge/Java-25-orange)
![License](https://img.shields.io/badge/license-MIT--0-green)

*Place a machine. Pick your fate. Walk through the portal.*

</div>

---

## 🏰 What is CrypTale?

Players place a **Dungeon Machine**, choose a **tier**, a **size**, a number of **floors** and a **difficulty**, then step
through its portal into **their own dungeon**, generated on the fly in a private instance.

> 🚪 Rooms to clear → 💀 a boss → 💰 a gold loot room behind it.

Every dungeon is different. **Same seed + same settings = same dungeon**, block for block, and same loot.

---

## ✨ Features

### 🗺️ Dungeons
- Procedural layouts: rooms, corridors and stairs, **1 to 5 floors** going down like a crypt
- Rooms **lock behind you** and open when their last monster dies; an abandoned fight resets
- **Boss** on the last floor, then a **gold loot room** with three chests
- Indestructible dungeon blocks (except in Creative)
- Relaunch cooldown per player

### 🎚️ Difficulty

| Mode | Lives | Loot |
|------|-------|------|
| 🛡️ **Normal** | 3 by default, respawn in the start room | Standard odds |
| ☠️ **Hardcore** | None: one death and you're out | Every chance ×2 |

### 🏛️ Tiers

| Tier | Look |
|------|------|
| Beginner | 🪨 Stone crypt |
| Easy | 🏜️ Sandstone temple |
| Intermediate | 🌊 Shale depths |
| Hard | 🌋 Volcanic forge |
| Elite | 🌑 Slate sanctum |

- ➕ **Add, remove, rename** tiers (1 to 20). Tiers past the 5th start from the Elite defaults
- 🧱 **12 blocks per tier** (walls, floors, columns, stairs, lanterns, braziers, torches...), set by **drag and drop**
  from the Creative inventory
- 👹 Own **boss**, **monsters** and **loot pools** for each tier

### 💎 Loot

| Chest | Drops |
|-------|-------|
| 📦 Common | Always |
| 🎁 Rare | By chance |
| 👑 Epic | By chance, one legendary item |

- Chances follow the **tier count**: set the first and the last tier, the others fall in between
- **Bigger dungeons, better odds**. A floor chance (0.1 %) keeps even a 1×1 dungeon worth a try
- 🔥 The hardest tier, max size, Hardcore: **an epic every time**
- Pools filled **in game**, by drag and drop

### 🛠️ Admin

| Command | What it does |
|---------|--------------|
| `/cryptale config` | In-game admin panel: Machine, Gameplay, Performance, Tiers, Monsters, Loot, with live odds |
| `/cryptale resetcooldown <player>` | Ends a player's relaunch cooldown (console too) |

🔒 Operators only (or players given the permission node). Everything is saved to `CrypTale.json`.

---

## 📥 Install

1. ⬇️ Download the latest **`CrypTale-x.y.z.jar`** from [Releases](../../releases/latest)
2. 📂 Drop it into your server's plugin folder and restart
3. 💰 Open `/cryptale config` → **Loot** and fill the pools (empty by default)
4. 🎮 `/give CrypTale_Dungeon_Machine`, place it, press **F**

> **Requires** Hytale server **0.7.5+** (built against 0.7.6).

---

## 🐛 Feedback

Found a bug or have an idea? Open an [issue](../../issues).

---

## 🤝 Credits

Made by **[OzL Prod](https://ozlprod.click)**.

Built with the help of **Claude** (Anthropic), my AI pair programmer for the design, the code and the reviews. 🤖

---

<div align="center">

📜 **MIT-0**: use it, change it, ship it. No attribution required.

</div>
