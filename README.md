# FANTASTICALLY INTEGRATED LOAD-ORDER FOR YOU
###### If you would like to see the general contents of the list, it is available at [Load Order Library](https://loadorderlibrary.com/lists/filfy-fantastically-integrated-load-order-for-you) for quick viewing without downloading.

| RECOMMENDED SPECS | REQUIRED SPECS |
| ----------- | ----------- |
| <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/4db34405eeaca0239ac27c0665dd9c4c28fed357/FILFY/Icons/SpecSheet_CPU_FILFY.svg" width="24"> &nbsp; Intel Core i7-9700K | <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/5265583b7a73410aa184bfafb76d1cca86bfc84e/FILFY/Icons/SpecSheet_CPU_FILFY_REQUIRED.svg" width="24"> &nbsp; Intel Core i3-8100 |
| <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/77168c4033189e900831515fa527c1bb1ae49b19/FILFY/Icons/SpecSheet_GPU_FILFY_RECOMMENDED.svg" width="24"> &nbsp; GeForce GTX 1080Ti | <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/77168c4033189e900831515fa527c1bb1ae49b19/FILFY/Icons/SpecSheet_GPU_FILFY_REQUIRED.svg" width="24"> &nbsp; GeForce GTX 660 |
| <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/7b2db02fb47d89f7d002aaf4c3a8523f79c1ec0e/FILFY/Icons/SpecSheet_RAM_FILFY_RECOMMENDED.svg" width="28"> &nbsp; 32GB DDR4 | <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/7b2db02fb47d89f7d002aaf4c3a8523f79c1ec0e/FILFY/Icons/SpecSheet_RAM_FILFY_REQUIRED.svg" width="28"> &nbsp; 8GB DDR4 |
| <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/7b2db02fb47d89f7d002aaf4c3a8523f79c1ec0e/FILFY/Icons/SpecSheet_Storage_FILFY_RECOMMENDED.svg" width="24"> &nbsp; 1TB NVME (PCIE Gen4x4) | <img src="https://raw.githubusercontent.com/RevontuletCXVII/Image-Vault/7b2db02fb47d89f7d002aaf4c3a8523f79c1ec0e/FILFY/Icons/SpecSheet_Storage_FILFY_REQUIRED.svg" width="24"> &nbsp; 1TB SSD (SATA 3) |

---

### TABLE OF CONTENTS 
###### You can skip to any desired section with the table of contents below. If you have questions not answered in the Common Issues section, please ask in our public [Discord Server](https://discord.gg/ag6FSESCK6).

| TABLE OF CONTENTS |
| ----------- |
| 1. [Feature Overview](#feature-overview) |
| 2. [Wabbajack Installation](#wabbajack-installation-guide) |
| 3. [FILFY Installation](#filfy-installation-guide) |
| 4. [Gameplay Adjustments](#gameplay-adjustments) |
| 5. [Shortcut Keys](#shortcut-keys) |
| 6. [Bundled Tools](#bundled-tools) |
| 7. [Common Issues](#common-issues) |
| 8. [To-Do List](#to-do-list) |
| 9. [Credits](#credits) |

---

### FEATURE OVERVIEW
###### This is a quick summary of key features added by this mod, with GIFs!

* GRAPHICS ARE GOOD BUT RUN ON MOST THINGS
  * COMMUNITY SHADERS IS INCLUDED
  * THE SKYRIM UPSCALER COMES W/ DLSS, FSR, AND XESS
* THE UI IS REALLY PRETTY
    * GOTTA LOVE AURA AND KOMEGAKI
    * LOOK AT THIS HAWT MAP
    * AND THIS SELECTION WHEEL
* COMBAT IS SPICY NOW
    * DODGE
    * COMBO ATTACKS
    * ENEMIES ARE REALLY SCARY
    * AND THERE ARE A LOT OF THEM
* EXPLORING IS FUN AGAIN
   * PARAGLIDING
   * WALKING ON WATER
   * LOTS OF NEW LOCATIONS
   * EVEN UNMARKED ONES THAT ARE SUPER HIDDEN
   * EVEN EVEN NEW WORLDSPACES
* LOTS OF OVERHAULS
  * PERKS
  * CRAFTING
  * TRAINING
  * LEVELING
  * CITIES, OUTSKIRTS, AND TOWNS
* I'M SURE THERE'S MORE
  
---

### WABBAJACK INSTALLATION GUIDE
###### This list requires Skyrim Anniversary Edition, or all of the Creation Club content downloaded, and will run SSE version 1.6.640. It should automatically downgrade for you when you run the Wabbajack, so you are safe to install whatever the latest version on Steam is (1.6.1170 as of writing). It will also take around 450GB of disk space, 150GB for Downloads and 300GB for the remaining Deployments.
1. Install copies of `TESV: Skyrim Special Editions` and `Skyrim Special Edition: Creation Kit` via Steam. It is recommended that you fully delete your old Skyrim Special Edition game folder and start from fresh. You do not need to ever use the Creation Kit, and a copy is automatically added to your Steam Library when you purchase Skyrim Special Edition.

    ![Steam-SSEAndCK](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Steam-SSEAndCK.png "Steam-SSEAndCK")
    * Your `\Skyrim Special Edition` folder should look like this:
   
    ![Windows-SkyrimRoot](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-SkyrimRootCK.png "Windows-SkyrimRoot")
3. Launch Skyrim to download all of the AE content from the Main Menu.
    * Do not re-validate files *after* downloading all of the content via the Main Menu. Rare Curios in Steam and in Skyrim are two different versions. Your `\Skyrim Special Edition\Data` folder should contain approximately 178 items and look like this:
      
        ![Windows-SkyrimData](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-SkyrimDataCK.png "Windows-SkyrimData")
4. Create a Folder for where you wish to install Wabbajack (non-System, non-Root directory) and another for where you wish to install the modlist contents (non-System directory). Examples are in both a picture and in table form below.
   
    ![Windows-EmptyFolderStructure](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/Windows-EmptyFolderStructure.png "Windows-EmptyFolderStructure")

| CORRECT FOLDER STRUCTURE | INCORRECT FOLDER STRUCTURE |
| ----------- | ----------- |
| `D:\Wabbajack\Wabbajack.exe` | `C:\Wabbajack.exe` |
| `C:\Wabbajack\Wabbajack.exe` | `C:\Windows\Wabbajack.exe` |
| `D:\Wabbajack\FILFY\{modlist-contents}` | `C:\Windows\FILFY\{modlist-contents}` |
| `C:\FILFY\{modlist-contents}` | `C:\{modlist-contents}` |

4. Launch the Wabbajack executable and it will download the core files and alter your folder structure to look like this.
   
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

### GAMEPLAY ADJUSTMENTS
###### This is an explaination of core gameplay altering modifications and adjustments, this is not comprehensive.

* THE UI IS REALLY PRETTY
    * GOTTA LOVE AURA AND KOMEGAKI
    * LOOK AT THIS HAWT MAP
    * AND THIS SELECTION WHEEL
* LOTS OF OVERHAULS
  * PERKS
  * CRAFTING
  * TRAINING
  * LEVELING
  * CITIES, OUTSKIRTS, AND TOWNS
* I'M SURE THERE'S MORE

#### Movement & Combat

* True Directional Movement allows for natural, fluid Third Person gameplay.
  * Combined with SmoothCam, you can now lock onto targets or free-aim your bow like never before.
  * With various Elden based mods and Valhalla, you can now block, parry, and reflect different attacks. You can role-play as a jedi swatting arrows.
* MCO and different movesets have been added, and they vary by race. Combat feels much more modern.
* Paragliding has been added, feel free to glide like the Nintendon't hero that you aren't.
* Enemies have been added from many different sources, such as Mihail and 4th Unknown. There are all sorts of Morrowind and Oblivion enemies re-introduced.
  * Some are scary. The world is unleveled. Be careful out there.

#### Exploration

* New Worldspaces
  * Bruma, Wyrmstooth, Falskaar, New Vominheim, Sirenroot, and multiple more...
* There are now many more unmarked locations for you to discover in the game and find special loot.
* Survival Mode Improved greatly alters the Survival Creation Club content, better integrating it into your game.
  * It also disables fast travel. I have therefore added the ability to fast travel if you aim your cursor at a road sign for a small fee. You can also travel to many more locations with ferries and carriages.
  * You can also fly around via your paraglider as mentioned above, so there's that...
  * If you really hate this, you can go to the MCM for Unlimited Fast Travel and enable the `When disabled via scripts/console` option.

#### Graphics

* Community Shaders is used as a base, combined with the Skyrim Upscaler, allowing you to use DLSS, FSR, or XeSS. This allows you to use this modlist on a very large range of hardware.
  * DynDOLOD is generated, improving the distant visuals compared to vanilla.
  * BethINI is also included, so you can safely adjust your graphical settings as you desire.
* 2K textures are shipped for almost everything included in the game. With the upscaler, this allows you to have decent performance with decent visuals at the same time. You can also download higher resolution versions of these if desired.
* Base Object Swapper is used extensively, meaning that the diversity of things in the wild is increased. This is for both objects for for animals. There are 4 different colors of Horkers, if you feel the need to catch them all.

#### "Cheating" Adjustments

* I absolutely hate running out of stamina while sprinting when I'm not even in combat, so I have three plugins enabled that are "cheats." These are desired for my own form of gameplay, but are easily disabled if you do not want them in your playthrough. They are shown below:

    ![MO2-CheatPlugins](https://raw.githubusercontent.com/AllstaRawR/FILFY/main/images/MO2-CheatPlugins.png "MO2-CheatPlugins")

---

### SHORTCUT KEYS
###### Below is a _hopefully_ comprehensive list of all shortcut keys added in the modlist.

* Mod Added/Adjusted Shortcuts
    * `PageDown`: Skyrim Upscaler
    * `PageUp`: ReShade
    * `Home`: dMenu
    * `Backspace`: Immersive Equipment Displays
    * `End`: Community Shaders
    * `Delete`: Open Animation Replacer
    * `O`: oBody Menu
    * `R`: Sheathe/Unsheathe (you can only draw/sheathe when pressing this button)
    * `T`: Dodge (must be unsheathed)
    * `Y`: Taunt
    * `U`: Character Stat Menu
    * `H`: Call Horse
    * `L`: Toggle Lantern Light
    * `;`: Teleport Followers
    * `'`: Swiftly Order Swad
    * `=`: Animated Interactions Menu
    * `F6`: Toggle UI
    * `F7`: KreatE (Weather adjustment and more)
* Vanilla Shortcuts
    * `Tab` -> `T`: Waiting (you press the wait button, `T`, while inside of the `Tween Menu`)
    * `Q`: Favorites
    * `I`: Inventory
    * `P`: Spells
    * `F`: First/Third Person Toggle
    * `J`: Journal
    * `C`: Auto-Run
    * `M`: Map
    * `/`: Skill Menu
    * `~`: Console Commands
    * `F12`: Steam Screenshot

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
* There are more included but hidden inside of the launcher. This is because I did not bundle their install files. If you would like to add some of them back, feel free. Examples include zEdit, Wrye Bash, and DynDOLOD.

---

### COMMON ISSUES
###### Read this *before* you make a bug report or GroundAura will answer you passive-aggressively.

* Rare Curios: `Unable to Download Data_ccgssse037-curiosesl/bsa`
  * Solution: Delete the `ccgssse037-curios` BSA and ESL files, then open Skyrim to re-download the AE content. **Do not** re-verify files via Steam afterwards, or you will have to repeat this step.
* The game reloads my save twice when I'm outside and trying to load a save! It must be broken.
  * No, this is actually an intentional fix to help with save file reloading bugs. If you load an exterior save, it will load twice.
* Long Load Times
  * Solution: Go back to [Steps 6-8](#filfy-installation-guide). Did you properly wait for this?
* Lots of plugins are disabled. What the heck?
  * You can restore the load order from the backup. You click the yellow arrow next to the active plugin counter and then restore from a recent backup stored with the Wabbajack.
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
- [x] Seperate out all "cheat" mods to their own section
- [x] Resolve DLSS/FSR/XeSS issues
- [ ] Update GamePlay Adjustments in the ReadMe
- [ ] Update Feature Overview in the ReadMe
- [ ] Add brief GIFs about each added feature
- [ ] Seperate out all "articstic nudity" but SFW per Wabbajack mods to their own section
- [ ] SkyPatch RACE records to remove ~40 plugins and clear the last unresolved conflicts
- [ ] Update all currently installed mods

#### IMPROVEMENTS
- [ ] Integrate `Conflicts Check - Static`, `Conflicts Check - Dynamic`, & `SSEEdit Output` into Nexus Mods, removing them from the inlined Wabbajack files.
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
- [Ra2Phoenix](https://www.nexusmods.com/skyrimspecialedition/users/111052?tab=user+files&BH=1) for their assistance with learning LAND and NAVM editing in the CK,
- [Arthmoor](https://www.nexusmods.com/skyrimspecialedition/users/684492?tab=user+files&BH=1) for their explanation on how weird things work, like EDIDs and papyrus,
- [GroundAura](https://www.nexusmods.com/skyrimspecialedition/users/97658973?tab=user+files&BH=1) for listening to me rant about frustrations and encouraging me to try new things,
- [Revontulet](https://www.nexusmods.com/starfield/users/51658166?tab=user+files?tab=user+files&BH=1) for constantly thinking I'm making innuendos and making graphics pretty,
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
