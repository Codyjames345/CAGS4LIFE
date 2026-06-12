# CAGS4LIFE

A private survival server built around **Create** and tech mods — automate everything, build factories, ride trains, and survive together. Nothing serious really, I created this server with the intent to participate in a lil tomfoolery here and there.

Note - you have to be a member of my Discord server to join this server, _don't even think about it bots!_. This is enforced by a whitelist managed by the Simple Discord Link plugin's access control.

**Minecraft 1.21.1 · neoforge-21.1.233**

---

## Joining for the first time

### 1. Download the modpack

Go to the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases) and download one of:

- **`CAGS4LIFE-client-updater.exe`** (or `.py`) — the updater can install from scratch, no zip needed (see [Updating](#updating) below)
- **`CAGS4LIFE-2.1.0-client.zip`** — extract manually into your instance folder (see below)
- **`CAGS4LIFE-2.1.0-curseforge.zip`** — import directly into the CurseForge launcher

### 2. Install it

**Importing the CurseForge zip (easiest):**
1. Open the CurseForge launcher and click **Create Custom Profile** → **Import**.
2. Select `CAGS4LIFE-2.1.0-curseforge.zip` and let it install.

**Extracting the client zip manually:**

A launcher that supports separate instances (like [CurseForge](https://www.curseforge.com/download/app)
or [Prism Launcher](https://prismlauncher.org/)) is strongly recommended. The vanilla Minecraft
launcher shares one `.minecraft` folder across all versions, so installing mods there affects
every version you play.

1. Create a new **neoforge-21.1.233** instance.
2. Open the instance folder (usually right-click → "Open Folder" or similar).
3. Extract the contents of `CAGS4LIFE-2.1.0-client.zip` into that folder —
   `mods`, `resourcepacks`, and `config` should land at its root.

**Using the vanilla launcher:**
1. Install neoforge-21.1.233 — it will create a new profile automatically.
2. Extract the zip contents into your `.minecraft` folder (`%AppData%\.minecraft` on Windows,
   `~/Library/Application Support/minecraft` on macOS, `~/.minecraft` on Linux).
3. Note: mods installed here are shared with all other versions in the vanilla launcher.

Also save **`CAGS4LIFE-client-updater.py`** (or the `.exe`) somewhere easy to
find — you'll use it to update later.

### 3. Connect

Launch your NeoForge profile and connect to **`cags4.life`**.

---

## Updating

Run `CAGS4LIFE-client-updater.py` (requires [Python 3.8+](https://www.python.org/downloads/))
or `CAGS4LIFE-client-updater.exe`. It checks for the latest version, shows you what changed,
and installs automatically. Works for both updates and fresh installs — if no modpack version is
detected in your folder it will download everything from scratch.

> **First time running the updater?** Point it at the folder that contains your `mods` directory —
> this is the instance folder in CurseForge/Prism, or `.minecraft` in the vanilla launcher.

Alternatively, download and extract a release zip from the [Releases page](https://github.com/Codyjames345/CAGS4LIFE/releases).

---

## Community

- Live map: https://map.cags4.life

---

## Requirements

| | |
|---|---|
| Minecraft | 1.21.1 |
| Mod loader | neoforge-21.1.233 |
| Python (updater only) | 3.8 or newer |

---

<!--
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  MODPACKCTL — PACK CREATOR NOTES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

All __PLACEHOLDER__ tokens in this file are replaced automatically by modpackctl
when you run `update`, `release`, or `publish` (client builds only).

README PLACEHOLDERS
───────────────────
  CAGS4LIFE      → settings.modpack_name
  CAGS4LIFE       → settings.file_prefix, falling back to settings.modpack_name
  1.21.1 → Minecraft version from the commit (e.g. 1.21.1) — kept in sync on MC version changes
  neoforge-21.1.233         → Full modloader id (e.g. neoforge-21.1.229)       — kept in sync on modloader changes
  NeoForge    → Loader name only (e.g. NeoForge)                 — kept in sync on modloader changes
  2.1.0    → Modpack version (e.g. 1.2.0)                     — kept in sync on every build
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
