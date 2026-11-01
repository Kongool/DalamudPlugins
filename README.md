# DalamudPlugins

One custom plugin repository for Kongool's Dalamud plugins.

## Install

1. In-game, open `/xlsettings` → **Experimental** → **Custom Plugin Repositories**.
2. Add this URL, tick **Enabled**, and save:

   ```text
   https://raw.githubusercontent.com/Kongool/DalamudPlugins/main/repo.json
   ```

3. Open `/xlplugins` and install a plugin.

## Plugins

| Plugin | Internal name | Source |
|---|---|---|
| Mercury | `Mercury` | [Kongool/Mercury](https://github.com/Kongool/Mercury) |
| Minerva | `Minerva` | [Kongool/Minerva](https://github.com/Kongool/Minerva) |
| Parcae | `AutoFateGrind` | [Kongool/Parcae](https://github.com/Kongool/Parcae) |

## Publishing an update

After publishing a plugin's GitHub release, update its entry in `repo.json`: `AssemblyVersion` and the three `DownloadLink*` URLs. Dalamud offers the update once this file changes on `main`.
