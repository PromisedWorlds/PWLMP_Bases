# PromisedWorldsBases
Kerbal Konstructs bases for the Promised Worlds LMP server. Also contains ModuleManager patches to ensure compatibility.

## Base List
### (Coming Soon) Jamietown
From the original Promised Worlds Science mode LMP server, Jamietown Base returns! This launchsite on Minmus is excellent for taking advantage of the low gravity to launch massive crafts.

We are planning a community event to deliver base parts to Minmus, after which Jamietown will be unlocked (an update will re-add it).

<img width="1920" height="1080" alt="Jamietown Base Overview" src="https://github.com/user-attachments/assets/a97bc6c2-383d-4369-8e74-bf79d49499e8" />

## ModuleManager Patches
- Disables Parallax collisions, to make sure all players have the same collisions.
- Adds a configuration for BetterTimeWarp Continued for 0.999x physics warp. Use this when your game is lagging (yellow time) - it will be more visually laggy, but your physics will be more stable.

# Dependencies
- [Kerbal Konstructs](https://github.com/KSP-RO/Kerbal-Konstructs)
- [Colony Blocks and Platforms for KK](https://spacedock.info/mod/3302/Colony%20Blocks%20and%20Platforms%20for%20KK)
- [Omega's Stockalike Structures: No Textures Required](https://spacedock.info/mod/2061/Omega's%20Stockalike%20Structures:%20No%20Textures%20Required)
- For ModuleManager patches: [ModuleManager](https://github.com/sarbian/ModuleManager/releases)

# Installation
Install all dependencies, and put the PromisedWorldsBases folder from GameData into your KSP's GameData directory.

# Users: Open the Base in Kerbal Konstructs
You must open each launchsite before you can launch from it.
1) In the editor, click on the KK button
  <img width="1920" height="1080" alt="Click the KK button" src="https://github.com/user-attachments/assets/9ad74887-8960-4660-8575-32733d9b4d46" />
2) In the window that pops up, select the desired launchsite (1), and in the launchsite panel click "Open Base for 0 funds" (2).
 <img width="1172" height="865" alt="Click open base" src="https://github.com/user-attachments/assets/80144ed1-310f-4958-b5b9-05ebbe2112d2" />
3) To launch, hover over the launch button, and click Launch on the desired launchsite in the dropdown menu. You may have to scroll.
  <img width="444" height="179" alt="Hover over the launch button to open the dropdown" src="https://github.com/user-attachments/assets/1e25dff7-7123-4208-8da4-ebe187fd4e2a" />
  <img width="444" height="389" alt="Click the launch button on the desired launchsite" src="https://github.com/user-attachments/assets/736e54a2-5090-4712-be3c-2e0f3d89a777" />


# Maintainers: Adding a New Base
To add a new base:
1) Create the base in game in Kerbal Konstructs.
2) Add it in a new folder under GameData
3) Add a description and screenshot in the Base List here
4) Commit these changes to the GitHub repository
5) Create a new .zip folder with a new version number
6) Create a new release on GitHub, and upload that zip where it says to upload binaries.
