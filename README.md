# Vibe Editing OS

Turn raw talking-head clips into finished short-form reels, edited in **your** style, inside the Claude desktop app.

## Install (no Terminal needed), version 0.7.2
1. Install the **Claude desktop app**, open the **Code** tab, and start a **local** session in any folder.
2. Paste this message and send it:

> Please set up the Vibe Editing OS plugin for me. In my user settings file `~/.claude/settings.json` (create it if missing, keep everything already in it), add the marketplace `"vibe-editing-os": {"source": {"source": "url", "url": "https://raw.githubusercontent.com/namansoniai/vibe-editing-os-setup/main/.claude-plugin/marketplace.json"}, "autoUpdate": true}` under `extraKnownMarketplaces`, and add `"vibe-editing-os-setup@vibe-editing-os": true` under `enabledPlugins`. If you need my permission to edit that file, ask me. Then tell me to start a new session.

3. Claude asks permission to change its own settings: click **Allow**.
4. Start a **new session**. If the plugin isn't active yet, open **+ → Plugins → Add plugin** and install **vibe-editing-os-setup**.
5. Type `/vibe-editing-os-setup:setup` and paste your licence key from the purchase email when asked (`VEOS-XXXX-XXXX-XXXX-XXXX`; lost it? https://veos-licence.shipwithoutcode.workers.dev/find-key). One key works on 2 computers; to switch computers, ask Claude to "move my licence" on the old one. This one-time install takes 15–20 min (~3.6 GB).
6. When it's done, start a **new session** (Claude loads the editor's skills then).
7. Type `/vibe-editing-os:playbook` to build your editing playbook.
8. Type `/vibe-editing-os:reel` and give it the folder with your raw clips.
