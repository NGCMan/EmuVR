# Installation

1. Download the following archives;
   * EmuVR base archive (EmuVR 1.0.1.7z)
      * (Latest download is always available in the official EmuVR Discord server)
   * Approved Retroarch version (RetroArch.7z)
     * http://buildbot.libretro.com/stable/1.7.5/windows/x86_64/RetroArch.7z
2. Create a folder for EmuVR (for this example, we'll use c:\EmuVR, but it can exist anywhere).
3. Extract the contents of **EmuVR 1.0.1.7z** to **c:\EmuVR**
   * Note: If you end up with c:\EmuVR\EmuVR, move everything out of there into c:\EmuVR. It should look like this;
   ![](/images/install_emuvr_folder.png)
4. Extract **RetroArch.7z** to **c:\EmuVR\Retroarch**
5. Copy your games to **c:\EmuVR\Games**. In this example, we can use the following SNES homebrew game, "Hilda" from https://gamejolt.com/games/hilda/162284 (you can use any rom(s) you like).
   1. For this example, create **c:\EmuVR\Games\snes**
      * The name of the folder doesn't matter, as long as it's descriptive.
      * Each console will have it's own folder, e.g. "n64", "genesis", etc.
      * You can delete the default "SystemX/Y/Z" folders.
   2. Move the .zip (or .sfc, etc) into **c:\EmuVR\Games\snes**
      * Note: EmuVR loads labels for all of your games into video memory at launch. As such, adding a large number of games could cause stability issues, including slowness and crashing. There is no known upper limit, but keep in mind that migrating a full list of roms from a previous library is not recommended (e.g., thousands of games).
6. Add games to EmuVR
   1. Run **C:\EmuVR\Game Scanner\Game Scanner.exe**
   2. Click "Attempt Autofill"
   3. Make sure **c:\EmuVR\Games\snes** has been added, it's Media is "SNES", and a related Core is selected.
      * In this case, I'm going to manually select "Nintendo - SNES / Famicom (Snes9x)" because I've tested it and it works well.
   4. Click "Save Changes".
   5. Click "Download Missing Cores" (wait for the download to complete and click "Ok")
   6. Click "Scan Games for EmuVR" (Wait for the scan to complete, then click "Ok")
7. Run **C:\EmuVR\EmuVR.exe** and make sure your consoles and carts are available
   * If you would like to run in Desktop Mode, execute "Force Desktop.exe" in the same place as EmuVR.exe. 

# Adding games after the initial install

1. Run **C:\EmuVR\Game Scanner\Game Scanner.exe**
2. Click "Attempt Autofill"
3. Make sure the folders you've added to **C:\EmuVR\Games** have been added. If not, click on "Add Folder..." and add it.
   * Make sure to select the correct **Media** type and **Core**
4. Click "Save Changes".
5. Click "Download Missing Cores" (wait for the download to complete and click "Ok")
6. Click "Scan Games for EmuVR" (Wait for the scan to complete, then click "Ok")

# Customizing game labels, posters, etc

Please see [this document](custom.md).

# Troubleshooting

Please see [this document](troubleshooting_known-issues.md).
