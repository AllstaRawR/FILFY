# Fantastically Integrated Load-order For You
###### If you would like to see the general contents of the list, it is available at [Load Order Library](https://loadorderlibrary.com/lists/filfy-fantastically-integrated-load-order-for-you) for quick viewing without downloading.

| Recommended Specs | Required Specs |
| ----------- | ----------- |
| ![Recommended CPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/CPU-Purple.svg "CPU-Purple") &nbsp; Intel Core i7-9700K | ![Required CPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/CPU-White.svg "CPU-White") &nbsp; Intel Core i3-8100 |
| ![Recommended GPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/GPU-Purple.svg "GPU-Purple") &nbsp; GeForce GTX 1080Ti | ![Required GPU - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/GPU-White.svg "GPU-White") &nbsp; GeForce GTX 660 |
| ![Recommended RAM - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-Purple.svg "RAM-Purple") &nbsp; 32GB | ![Required RAM - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-White.svg "RAM-White") &nbsp; 8GB |
| ![Recommended Storage - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-Purple.svg "RAM-Purple") &nbsp; 1TB NVME | ![Required Storage - ](https://raw.githubusercontent.com/AllstaRawR/FILFY/4bf878b223d43d99f5e74cdc01645cf986e50990/images/RAM-White.svg "RAM-White") &nbsp; 600GB HDD |

---

### Wabbajack Installation Guide
###### This list requires Skyrim Anniversary Edition, or all of the Creation Club content downloaded, and will run SSE version 1.6.640 It should automatically downgrade for you when you run the Wabbajack, so you are safe to install whatever the latest version on Steam is (1.6.1170 as of writing).
* Install a copy of Skyrim via Steam. It is recommended that you fully delete your old Skyrim Special Edition game folder and start from fresh.
* Launch Skyrim to download all of the AE content from the Main Menu.
    * Do not re-validate files *after* downloading all of the content via the Main Menu. Rare Curios in Steam and in Skyrim are two different versions.
*  Create a Folder for where you wish to install Wabbajack (non-System, non-Root directory) and another for where you wish to install the modlist contents (non-System directory). Examples are below.
*  Launch the Wabbajack executable and select FILFY in the Gallery. You will have to select "Show Unofficial Lists". You can then select the directory for `{modlist-contents}` that you made in the step above. Click the `Play` button.
*  If the above steps completed without error, you can now open `ModOrganizer.exe` in your `FILFY\{modlist-contents}` folder and proceed to the FILFY Launch Guide below.
  
| Good | Bad |
| ----------- | ----------- |
| `D:\Wabbajack\Wabbajack.exe` | `C:\Wabbajack.exe` |
| `C:\Wabbajack\Wabbajack.exe` | `C:\Windows\Wabbajack.exe` |
| `D:\Wabbajack\FILFY\{modlist-contents}` | `C:\Windows\FILFY\{modlist-contents}` |
| `C:\FILFY\{modlist-contents}` | `C:\{modlist-contents}` |

---

### FILFY Launch Quide
* In Progress...

--- 

### Common Issues (Read this *before* you make a bug report)
* Rare Curios
* Non-System Non-Root folder
* In Progress...

---

### To Do List

#### Immediate
- [x] Publish the list
- [x] Integrate the Game INIs
- [x] Integrate the SKSE INIs
- [x] Set up MenuMaid and MCM Recorder
- [x] Integrate the non-Patreon Skyrim Upscaler
- [ ] Update the GitHub ReadMe
- [x] Re-clean all plugins for safety (should be cleaned already)
- [x] Migrate all Modgroups to a subfolder to prevent accidental usage
- [ ] SkyPatch RACE records to remove ~40 plugins and clear the last unresolved conflicts
- [ ] Switch to SFCO3 to remove ~100 plugins
- [ ] Merge and compile w/ comments BOS swap replacers by mod to reduce file handle usage

#### Improvements
- [ ] Balance Experience scaling
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
- [Lizzy](https://www.wildlandermod.com/) for being nice and providing lovely Wabbajack advice.
