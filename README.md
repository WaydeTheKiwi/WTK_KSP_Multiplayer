# WTK_KSP_Multiplayer

🚀 **Kerbal Space Program + LunaMultiplayer Setup Guide**

Complete setup instructions for Kerbal Space Program with LunaMultiplayer (LMP) and mods using CKAN.

![KSP Folder Structure](./images/ksp_folder_example.png)

## 📋 Prerequisites

- Windows PC with Steam
- .NET Framework 4.8 or higher
- ~20GB free disk space (for clean + modded copies)
- Stable internet connection

## 🧹 Step 1: Clean KSP Installation

### Uninstall from Steam

1. Open Steam → Library
2. Right-click **Kerbal Space Program** → **Manage** → **Uninstall**

### Remove Leftover Files

Navigate to and delete any remaining files:

```
C:\Program Files (x86)\Steam\steamapps\common\Kerbal Space Program\
```

### Reinstall KSP

1. Reinstall KSP through Steam
2. Ensure **beta version is disabled**:
   - Right-click KSP → **Properties** → **Betas** tab → Set to **None**

![Steam Beta Settings](./images/steam_betas.png)

## 📁 Step 2: Create Game Copies

1. Navigate to your KSP installation:

   ```
   C:\Program Files (x86)\Steam\steamapps\common\Kerbal Space Program\
   ```

2. Copy the entire folder to:

   ```
   D:\Games\Kerbal Space Program_clean\
   ```

3. Copy again and rename to:
   ```
   D:\Games\Kerbal Space Program_Modded\
   ```

> 💡 **Important**: Keep the `_clean` copy untouched as a backup. Use only the `_Modded` copy for multiplayer.

## 🔧 Step 3: Verify .NET Framework

1. Press `Win + R`, type `cmd`, press Enter
2. Run: `dotnet --version`
3. If version is below 4.8, download from: https://dotnet.microsoft.com/download

![.NET Version Check](./images/dotnet_version.png)

## 🧩 Step 4: Setup CKAN Mod Manager

### Download and Install

1. Download `CKAN.exe` from: https://github.com/KSP-CKAN/CKAN/releases
2. **Move** `CKAN.exe` into your `Kerbal Space Program_Modded` folder
3. Run `CKAN.exe` from that location

### Initial Configuration

1. Select **KSP 1.12** ONLY (uncheck other versions)

![CKAN Compatible Versions - Default](./images/CKAN_compatible_versions_default.png)

Select only KSP 1.12 and click Continue:

![CKAN Compatible Versions - Updated](./images/CKAN_compatible_versions_updated.png)

2. Click **Yes** to check for updates
3. Refresh mod list if prompted

![CKAN Refresh Mod List](./images/CKAN_refresh_mod_list.png)

4. You may see a permission dialog - click **Yes**:

![CKAN Permission Handler](./images/CKAN_requires_permission_to_add_a_handler.png)

### Cleanup Game Instances

- Go to **Settings** → **Manage Game Instances**

![CKAN Game Instances - Default](./images/CKAN_game_instances_default.png)

- Remove all instances except `Kerbal Space Program_Modded`

![CKAN Game Instances - Updated](./images/CKAN_game_instances_updated.png)

## 📦 Step 5: Install Mod Pack

1. Download the mod list: `WTKKSPMultiplayerV1.ckan` from:
   https://github.com/WaydeTheKiwi/WTK_KSP_Multiplayer

2. In CKAN: **File** → **Install from .ckan**

![CKAN File Menu](./images/CKAN_file_menu.png)

3. Press **Apply**

![CKAN Change Set](./images/CKAN_change_set.png)

4. Confirm installation when prompted to overwrite:

![CKAN Overwrite Files](./images/CKAN_over_write_files.png)

## 🚀 Step 6: First Launch

### Launch KSP

- Click **Launch KSP** in CKAN, or run `KSP_x64.exe` from the modded folder

### What to Expect
**Happy flying, astronauts!** 🌌
