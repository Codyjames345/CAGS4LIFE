# CAGS4LIFE

A kitchen-sink modpack for the CAGS4LIFE community server. Build and automate with Create and Applied Energistics 2, cast spells with Ars Nouveau, take to the skies with Immersive Aircraft, fight epic bosses from Cataclysm, and cook up a feast with Farmer's Delight. Ships with Complementary Reimagined shaders and a full suite of performance and QoL mods — just install and play.

**Minecraft 1.21.1 · neoforge-21.1.229**

---

## Joining for the first time

### 1. Download the modpack

Go to the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases) and download one of:

- **`CAGS4LIFE-1.3.1-client.zip`** — extract manually into your instance folder (see below)
- **`CAGS4LIFE-1.3.1-curseforge.zip`** — import directly into the CurseForge launcher

### 2. Install it

**Importing the CurseForge zip (easiest):**
1. Open the CurseForge launcher and click **Create Custom Profile** → **Import**.
2. Select `CAGS4LIFE-1.3.1-curseforge.zip` and let it install.

**Extracting the client zip manually:**

A launcher that supports separate instances (like [CurseForge](https://www.curseforge.com/download/app)
or [Prism Launcher](https://prismlauncher.org/)) is strongly recommended. The vanilla Minecraft
launcher shares one `.minecraft` folder across all versions, so installing mods there affects
every version you play.

1. Create a new **neoforge-21.1.229** instance.
2. Open the instance folder (usually right-click → "Open Folder" or similar).
3. Extract the contents of `CAGS4LIFE-1.3.1-client.zip` into that folder —
   `mods`, `resourcepacks`, and `config` should land at its root.

**Using the vanilla launcher:**
1. Install NeoForge — it will create a new profile automatically.
2. Extract the zip contents into your `.minecraft` folder (`%AppData%\.minecraft` on Windows,
   `~/Library/Application Support/minecraft` on macOS, `~/.minecraft` on Linux).
3. Note: mods installed here are shared with all other versions in the vanilla launcher.

Also save **`CAGS4LIFE-client-updater.py`** (or the `.exe` if provided) somewhere easy to
find — you'll use it to update later.

### 3. Connect

Launch your NeoForge profile and connect to **`cags4.life`**.

---

## Updating

Run `CAGS4LIFE-client-updater.py` (requires [Python 3.8+](https://www.python.org/downloads/)).
It will check for updates, show you what changed, and install automatically.

> **First time running the updater?** Point it at the folder that contains your `mods` directory —
> this is the instance folder in CurseForge/Prism, or `.minecraft` in the vanilla launcher.

Alternatively, download and extract a release zip from the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases).

---

## Community

- Discord: __DISCORD_URL__
- Live map: https://map.cags4.life

---

## Requirements

| | |
|---|---|
| Minecraft | 1.21.1 |
| Mod loader | neoforge-21.1.229 |
| Python (updater only) | 3.8 or newer |

---

<!--
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  MODPACKCTL — PACK CREATOR NOTES (delete this section before publishing)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

All __PLACEHOLDER__ tokens in this file are replaced automatically by modpackctl
when you run `update`, `release`, or `publish` (client builds only).

README PLACEHOLDERS
───────────────────
  CAGS4LIFE      → settings.modpack_name
  CAGS4LIFE       → settings.file_prefix, falling back to settings.modpack_name
  1.21.1 → Minecraft version from the commit (e.g. 1.21.1) — kept in sync on MC version changes
  neoforge-21.1.229         → Full modloader id (e.g. neoforge-21.1.229)       — kept in sync on modloader changes
  NeoForge    → Loader name only (e.g. NeoForge)                 — kept in sync on modloader changes
  1.3.1    → Modpack version (e.g. 1.2.0)                     — kept in sync on every build
  https://github.com/Codyjames345/CAGS4LIFE/releases      → https://github.com/<user>/<repo>/releases
  Codyjames34526            → settings.author
  cags4.life    → settings.server_address
  __DISCORD_URL__       → settings.discord_url
  https://map.cags4.life           → settings.map_url

Set server_address, discord_url, and map_url in modpackctl.toml under [settings].
Remove any Community section lines whose placeholders you haven't set.

UPDATER TEMPLATE PLACEHOLDERS  (client-updater.example.py / server-updater.example.py)
─────────────────────────────
These are substituted when you run `bake-updater` (or as part of `release` / `publish`).
Write them as plain string literals in the template files.

  "__GITHUB_USER__"       → github.user
  "__GITHUB_REPO__"       → github.repo
  "CAGS4LIFE"      → settings.modpack_name
  "__LOGO_URL__"          → settings.logo_url (empty string if unset)
  "__ENABLE_SECRET__"     → True / False  (settings.enable_secret, default True)
  "__SECRET_VIDEO_URL__"  → settings.secret_video_url (defaults to Never Gonna Give You Up)
  "__ENABLE_RAINBOW__"    → True / False  (settings.enable_rainbow, default False)

  Server updater only supports: __GITHUB_USER__, __GITHUB_REPO__, CAGS4LIFE
-->
