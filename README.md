# FANTASTICALLY INTEGRATED LOAD-ORDER FOR YOU
###### If you would like to see the general contents of the list, it is available at [Load Order Library](https://loadorderlibrary.com/lists/filfy-fantastically-integrated-load-order-for-you) for quick viewing without downloading.

| RECOMMENDED SPECS | REQUIRED SPECS |
| ----------- | ----------- |
| ![Recommended CPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/CPU-Purple.svg "CPU-Purple") &nbsp; Intel Core i7-9700K | ![Required CPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/CPU-White.svg "CPU-White") &nbsp; Intel Core i3-8100 |
| ![Recommended GPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/GPU-Purple.svg "GPU-Purple") &nbsp; GeForce GTX 1080Ti | ![Required GPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/GPU-White.svg "GPU-White") &nbsp; GeForce GTX 660 |
| ![Recommended RAM - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-Purple.svg "RAM-Purple") &nbsp; 32GB | ![Required RAM - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-White.svg "RAM-White") &nbsp; 8GB |
| ![Recommended Storage - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-Purple.svg "RAM-Purple") &nbsp; 1TB NVME | ![Required Storage - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-White.svg "RAM-White") &nbsp; 1TB SSD |

---

### TABLE OF CONTENTS 
###### You can skip to any desired section with the table of contents below. If you have questions not answered in the Common Issues section, please ask in our public [Discord Server](https://discord.gg/ag6FSESCK6).

| TABLE OF CONTENTS |
| ----------- |
| 1. [Wabbajack Installation](#wabbajack-installation-guide) |
| 2. [FILFY Installation](#filfy-installation-guide) |
| 3. [Gameplay](#gameplay) |
| 4. [Shortcut Keys](#shortcut-keys) |
| 5. [Bundled Tools](#bundled-tools) |
| 6. [Common Issues](#common-issues) |
| 7. [To-Do List](#to-do-list) |
| 8. [Credits](#credits) |

---

### WABBAJACK INSTALLATION GUIDE
###### This list requires Skyrim Anniversary Edition, or all of the Creation Club content downloaded, and will run SSE version 1.6.640 It should automatically downgrade for you when you run the Wabbajack, so you are safe to install whatever the latest version on Steam is (1.6.1170 as of writing). It will also take around 450GB of disk space, 150GB for Downloads and 300GB for the remaining Deployments.
1. Install a copy of Skyrim via Steam. It is recommended that you fully delete your old Skyrim Special Edition game folder and start from fresh. Your `\Skyrim Special Edition` folder should look like this:
   
    ![Windows-SkyrimRoot](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-SkyrimRoot.png "Windows-SkyrimRoot")
3. Launch Skyrim to download all of the AE content from the Main Menu.
    * Do not re-validate files *after* downloading all of the content via the Main Menu. Rare Curios in Steam and in Skyrim are two different versions. Your `\Skyrim Special Edition\Data` folder should contain approximately 177 items and look like this:
      
        ![Windows-SkyrimData](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-SkyrimData.png "Windows-SkyrimData")
4. Create a Folder for where you wish to install Wabbajack (non-System, non-Root directory) and another for where you wish to install the modlist contents (non-System directory). Examples are in both a picture and in table form below.
   
    ![Windows-EmptyFolderStructure](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-EmptyFolderStructure.png "Windows-EmptyFolderStructure")

| CORRECT FOLDER STRUCTURE | INCORRECT FOLDER STRUCTURE |
| ----------- | ----------- |
| `D:\Wabbajack\Wabbajack.exe` | `C:\Wabbajack.exe` |
| `C:\Wabbajack\Wabbajack.exe` | `C:\Windows\Wabbajack.exe` |
| `D:\Wabbajack\FILFY\{modlist-contents}` | `C:\Windows\FILFY\{modlist-contents}` |
| `C:\FILFY\{modlist-contents}` | `C:\{modlist-contents}` |

5. Launch the Wabbajack executable and it will download the core files and alter your folder structure to look like this.
   
    ![Windows-FolderStructure](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-FolderStructure.png "Windows-FolderStructure")

---

### FILFY INSTALLATION GUIDE
###### This is a guide on how to actually install and play the game, once you finished with all Wabbajack setup.

1. Click `Browse` in Wabbajack, then select `Download Modlist` on FILFY in the Gallery to download. You will have to select `Show Unofficial Lists` for it to show up.
   
    ![WJ-BrowseToFILFY](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/WJ-BrowseToFILFY.png "WJ-BrowseToFILFY")
2. Once the download has finished, press the small play button in the same location to download the Wabbajack install file.
3. Select the directory for `{modlist-contents}` that you made above. Click the `Play` button.
    
    ![WJ-InstallFILFY](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/WJ-InstallFILFY.png "WJ-InstallFILFY")

4. If the above steps completed without error, you can now open `ModOrganizer.exe` in your `FILFY\{modlist-contents}` folder and launch Mod Organizer 2.

5. Click the `Run` button under the launch option of `Skyrim (SKSE)`, as shown below.
   
    ![MO2-Launch](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/MO2-LaunchSmall.png "MO2-Launch")

6. You will now get a splash screen that shows up to reassure you that SKSE is loading. It will likely take **_1-2 minutes_** to fully load.

    ![/SKSE-SplashScreen](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/SKSE-SplashScreenFixed.png "/SKSE-SplashScreen")
7. You will now be at a black full screen, showing that Skyrim itself has now launched and is in the process of loading all plugins. It will likely take **_2-3 minutes_** to fully load.
    * If this is the first time you have launched this modpack, the game will need to compile shaders between Step 4 and 5. This will take **_around 1 minute_** and slow your computer down considerably, but only needs to be done once.

    ![Skyrim-LaunchSmall](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Skyrim-LaunchSmall.png "Skyrim-LaunchSmall")
8. Skyrim will automatically load into your latest save file (or a new game if you do not have a save file). Congratulations, you are done!

--- 

### GAMEPLAY
###### This is an explaination of all core gameplay altering modifications and adjustments.

#### Immersive Adjustments

* Will
* Add
* Shortly

#### Non-Immersive Adjustments

* Will
* Add
* Shortly

#### "Cheating" Adjustments

I absolutely hate running out of stamina while sprinting when I'm not even in combat, so I have three plugins enabled that are "cheats." These are desired for my own form of gameplay, but are easily disabled if you do not want them in your playthrough. They are shown below:

![MO2-CheatPlugins](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/MO2-CheatPlugins.png "MO2-CheatPlugins")

---

### SHORTCUT KEYS
###### Below is a _hopefully_ comprehensive list of all shortcut keys added in the modlist.

1. Wow
2. So
3. Empty
   
---

### BUNDLED TOOLS
###### The various tools included with the Wabbajack, as well as a basic explaination of their use case.

* Creation Kit (with Creation Kit Platform Extended)
  * This is what Bethesda gave us to make mods, but better!
* SSEEdit
  * This is your go-to tool to see what might be going on inside of the plugins.
* BodySlide
  * This is to generate all of your hawt armor mod bodyslide files.
  * This modpack features oBody, so you will need to ensure that you use the HIMBO or 3BA `Zeroed Presets` when generating BodySlide files, as well as ensure that you build morphs.
* Nemesis
  * This is the current go-to animation generation tool. I would like to switch to Pandora, but it currently has caching issues.
* Beth INI
  * This can be run to adjust your INIs as desired for optimal quality and performance.
* Cathedral Assets Optimizer
  * This can be run to correct texture, mesh, and animation errors.
*  Others?!
  * There are more included but hidden inside of the launcher. This is because I did not bundle their install files. If you would like to add some of them back, feel free. Examples include zEdit, Wrye Bash, and 

---

### COMMON ISSUES
###### Read this *before* you make a bug report or GroundAura will answer you passive-aggressively.

* Rare Curios: `Unable to Download Data_ccgssse037-curiosesl/bsa`
  * Solution: Reopen Skyrim to download the AE content, then re-verify files via Steam.
* Long Load Times
  * Solution: Go back to [Steps 6-8](#filfy-installation-guide). Did you properly wait for this?
* Report additional errors in the Discord or Nexus Bug Tracker and I'll post them here!

---

### TO DO LIST
###### The never-ending list of things to fix, then to improve.

#### IMMEDIATE
- [x] Publish the list
- [x] Integrate the Game INIs
- [x] Integrate the SKSE INIs
- [x] Set up MenuMaid and MCM Recorder
- [x] Integrate the non-Patreon Skyrim Upscaler
- [x] Update the GitHub ReadMe
- [x] Re-clean all plugins for safety (should be cleaned already)
- [x] Migrate all Modgroups to a subfolder to prevent accidental usage
- [ ] SkyPatch RACE records to remove ~40 plugins and clear the last unresolved conflicts

#### IMPROVEMENTS
- [ ] Switch to SFCO3 to remove ~100 plugins
- [ ] Balance Experience scaling
- [ ] Merge and compile w/ comments BOS swap replacers by mod to reduce file handle usage
- [ ] Replace launch splash screen w/ an image that says something about the expected load times
- [ ] Create an icon for the modlist to show in the taskbar
- [ ] Link to the Discord and to the ReadMe through the ingame Main Menu
- [ ] Switch from StockGame to RootBuilder
- [ ] Convert remaining FLs to SkyPatcher to remove 100-200 plugins
- [ ] Covert remaining LLs to SkyPatcher to remove 250-500 plugins
- [ ] Update conflict resolution patches for new SkyPatcher situation and store their Source
- [ ] Split up Ryn's-JK's-Whiterun Outskirts for Czasior
- [ ] Resolve CustomRace issues (Generate FaceGen, fix hair sliders, add racial options, check on hair tint)
- [ ] Update DIALs per Elminster

---

### Credits
###### All of the people that I could not have done it without.
- [RobertGK](https://www.nexusmods.com/skyrimspecialedition/users/5544506?tab=user+files&BH=1) for their endless support,
- [ElminsterAU](https://www.nexusmods.com/skyrimspecialedition/users/167469?tab=user+files&BH=1) for their patience with my many edge case issues caused by my load orders size,
- [EllieBot](https://www.nexusmods.com/skyrimspecialedition/users/98998968?tab=user+files&BH=1) for their positive attitude when Rob was being too intense,
- [Ra2Phoenix](https://www.nexusmods.com/skyrimspecialedition/users/111052?tab=user+files&BH=1) for their assistance with learning LAND and NAVM editing in the CK, as well as how to properly minimize the conflict surface,
- [Arthmoor](https://www.nexusmods.com/skyrimspecialedition/users/684492?tab=user+files&BH=1) for their explanation on how weird things work, like EDIDs and papyrus,
- [GroundAura](https://www.nexusmods.com/skyrimspecialedition/users/97658973?tab=user+files&BH=1) for listening to me rant about frustrations and encouraging me to try new things,
- [JonathanOstrus](https://www.nexusmods.com/skyrimspecialedition/users/14649434?tab=user+files&BH=1) for the scripts that saved me so much pain dealing with masters,
- [Janquel](https://www.nexusmods.com/skyrimspecialedition/users/51448566?tab=user+files&BH=1) for their super secret secret-ness,
- [Czasior](https://www.nexusmods.com/skyrimspecialedition/users/9933289?tab=user+files&BH=1) for explaining the oddities of FOMODs,
- [Monops](https://www.nexusmods.com/skyrimspecialedition/users/17251819?tab=user+files&BH=1) for doing the same as Czasior, to the point that I keep confusing you two in my head,
- [Clearing](https://www.nexusmods.com/skyrimspecialedition/users/1148218?tab=user+files&BH=1) for their contribution to automating FOMODs,
- [Alaxouche](https://www.nexusmods.com/skyrimspecialedition/users/57127132?tab=user+files&BH=1) for being my punching bag,
- [ChickenMike](https://www.nexusmods.com/skyrimspecialedition/users/70500678?tab=user+files&BH=1) for all of the [C.R.A.P.](https://www.nexusmods.com/skyrimspecialedition/mods/106790)﻿,
- [MonkeyAngie](https://www.nexusmods.com/skyrimspecialedition/users/8184125?tab=user+files&BH=1) ﻿for asking me to make various mods multiple times,
- [Blackread](https://www.nexusmods.com/skyrimspecialedition/users/78985?tab=user+files&BH=1)﻿ for being a wonderful support and pointing out my errors,
- [Lizzy](https://www.wildlandermod.com/) for being nice and providing lovely Wabbajack advice,
- [Komegaki](https://www.nexusmods.com/skyrimspecialedition/users/80113953?tab=user+files?tab=user+files&BH=1) for your motivation and support, as well as graphical wizardry.
