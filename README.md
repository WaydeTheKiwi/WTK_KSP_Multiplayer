# WTK_KSP_Multiplayer

🚀 **Kerbal Space Program + LunaMultiplayer Setup Guide**

Complete setup instructions for Kerbal Space Program with LunaMultiplayer (LMP) and mods using CKAN.

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

## 🧩 Step 4: Setup CKAN Mod Manager

### Download and Install

1. Download `CKAN.exe` from: https://github.com/KSP-CKAN/CKAN/releases
2. **Move** `CKAN.exe` into your `Kerbal Space Program_Modded` folder
3. Run `CKAN.exe` from that location

### Initial Configuration

1. Select **KSP 1.12** ONLY (uncheck other versions)
2. Click **Yes** to check for updates
3. Refresh mod list if prompted

### Cleanup Game Instances

- Go to **Settings** → **Manage Game Instances**
- Remove all instances except `Kerbal Space Program_Modded`

## 📦 Step 5: Install Mod Pack

1. Download the mod list: `WTKKSPMultiplayerV1.ckan` from:
   https://github.com/WaydeTheKiwi/WTK_KSP_Multiplayer

2. In CKAN: **File** → **Install from .ckan**
3. Select the downloaded `.ckan` file
4. Confirm installation when prompted

## 🚀 Step 6: First Launch

### Launch KSP

- Click **Launch KSP** in CKAN, or run `KSP_x64.exe` from the modded folder

### What to Expect

- First launch takes several minutes
- "Loading Expansions" and ModuleManager setup will be slow
- If Parallax warning appears and won't close, press `ESC`

## ⚙️ Step 7: Configure Settings

### General Settings

- ✅ Enable **Advanced Tweakables**

### Graphics Settings

- **Terrain Detail**: High or Ultra
- **Texture Quality**: High or Full Res
- ✅ Enable **Terrain Scatters**
- **Terrain Scatters Quality**: High or higher

### Input Settings

- **Default Throttle (Pre-Launch)**: 100%

### Optional: Borderless Window

1. Turn **OFF** Fullscreen in KSP settings
2. In CKAN, hover over **Launch** button → **Edit Launch Command**
3. Set to: `KSP_x64.exe -popupwindow`

### Test Your Installation

- Create a new sandbox save
- Verify planets, mods, and UI are working correctly

## 🌐 Step 8: Connect to Multiplayer

1. From main menu, click **Luna Multiplayer**
2. Click the **+** button to add server
3. Enter server details:
   - **Address**: `ksp.waydethekiwi.com`
4. Enter your **Player Name**
5. Click the **Satellite icon** to connect

## 🎯 Success!

You're now ready to explore the Kerbal universe with friends! 🚀

## 🆘 Need Help?

- Check GitHub Issues for common problems
- Join our Discord for live support
- Ensure all steps were followed exactly as written

## 📝 Notes

- Keep your `_clean` copy for vanilla KSP or troubleshooting
- CKAN will manage mod updates automatically
- Server may have specific rules - check with administrators

---

**Happy flying, astronauts!** 🌌
