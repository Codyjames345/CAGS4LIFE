# CAGS4LIFE Modpack

A private survival server built around **Create** and tech mods — automate everything, build factories, ride trains, and survive together. Nothing serious really, I created this server with the intent to participate in a lil tomfoolery here and there.

Note - you have to be a member of my Discord server to join this server, _don't even think about it bots!_.

**Minecraft 1.21.1 · NeoForge 21.1.229**

---

## Joining for the first time

### 1. Download the modpack

Go to the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases) and download the latest **CAGS4LIFE-x.x.x-client.zip**.

### 2. Install it

A launcher that supports separate instances (like [CurseForge](https://www.curseforge.com/download/app) or [Prism Launcher](https://prismlauncher.org/)) is strongly recommended. The vanilla Minecraft launcher shares one `.minecraft` folder across all versions, so installing mods there affects every version you play.

**Using CurseForge, Prism, or similar:**
1. Create a new **NeoForge 21.1.229** instance.
2. Open the instance folder (usually right-click the instance → "Open Folder" or similar).
3. Extract the contents of the zip into that folder — `mods`, `resourcepacks`, and `config` should land at its root.

**Using the vanilla launcher:**
1. Install [NeoForge 21.1.229](https://neoforged.net/) — it will create a new NeoForge profile automatically.
2. Extract the zip contents into your `.minecraft` folder (`%AppData%\.minecraft` on Windows, `~/Library/Application Support/minecraft` on macOS, `~/.minecraft` on Linux).
3. Note: mods installed here are shared with all other versions in the vanilla launcher.

Also extract **`client-updater.py`** somewhere you can find it again — you'll use it to update later.

### 3. Connect

Launch NeoForge 21.1.229 and connect to **`cags4.life`**.

---

## Updating

Run `client-updater.py` (requires [Python 3.8+](https://www.python.org/downloads/)).
It will check for updates, show you what changed, and install automatically.

> **First time running the updater?** Point it at the folder that contains your `mods` directory — this is the instance folder in CurseForge/Prism, or `.minecraft` in the vanilla launcher.

---

## Live map

[map.cags4.life](https://map.cags4.life)

---

## Requirements

| | |
|---|---|
| Minecraft | 1.21.1 |
| Mod loader | NeoForge 21.1.229 |
| Python (updater only) | 3.8 or newer |
