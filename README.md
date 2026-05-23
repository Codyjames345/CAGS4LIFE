# CAGS4LIFE Modpack

A private survival server built around **Create** and tech mods — automate everything, build factories, ride trains, and survive together. Nothing serious really, I created this server with the intent to participate in a lil tomfoolery here and there.

Note - you have to be a member of my Discord server to join this server, _don't even think about it bots!_. This is enforced by a whitelist managed by the Simple Discord Link plugin's access control.

**Minecraft 1.21.1 · neoforge-21.1.229**

---

## Joining for the first time

### 1. Download the modpack

Go to the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases) and download one of:

- **`CAGS4LIFE-1.3.0-client.zip`** — extract manually into your instance folder (see below)
- **`CAGS4LIFE-1.3.0-curseforge.zip`** — import directly into the CurseForge launcher

### 2. Install it

**Importing the CurseForge zip (easiest):**
1. Open the CurseForge launcher and click **Create Custom Profile** → **Import**.
2. Select `CAGS4LIFE-1.3.0-curseforge.zip` and let it install.

**Extracting the client zip manually:**

A launcher that supports separate instances (like [CurseForge](https://www.curseforge.com/download/app)
or [Prism Launcher](https://prismlauncher.org/)) is strongly recommended. The vanilla Minecraft
launcher shares one `.minecraft` folder across all versions, so installing mods there affects
every version you play.

1. Create a new **neoforge-21.1.229** instance.
2. Open the instance folder (usually right-click → "Open Folder" or similar).
3. Extract the contents of `CAGS4LIFE-1.3.0-client.zip` into that folder —
   `mods`, `resourcepacks`, and `config` should land at its root.

**Using the vanilla launcher:**
1. Install [neoforge-21.1.229](https://neoforged.net/) — it will create a new profile automatically.
2. Extract the zip contents into your `.minecraft` folder (`%AppData%\.minecraft` on Windows,
   `~/Library/Application Support/minecraft` on macOS, `~/.minecraft` on Linux).
3. Note: mods installed here are shared with all other versions in the vanilla launcher.

Also save **`CAGS4LIFE-client-updater.py`** (or the `.exe` if provided) somewhere easy to
find — you'll use it to update later.

### 3. Connect

Launch your NeoForge profile and connect to **`__SERVER_ADDRESS__`**.

---

## Updating

Run `CAGS4LIFE-client-updater.py` (requires [Python 3.8+](https://www.python.org/downloads/)).
It will check for updates, show you what changed, and install automatically.

> **First time running the updater?** Point it at the folder that contains your `mods` directory —
> this is the instance folder in CurseForge/Prism, or `.minecraft` in the vanilla launcher.

Alternatively, download and extract a release zip from the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases).

---

## Live map

[__MAP_URL__](__MAP_URL__)

---

## Requirements

| | |
|---|---|
| Minecraft | 1.21.1 |
| Mod loader | neoforge-21.1.229 |
| Python (updater only) | 3.8 or newer |
