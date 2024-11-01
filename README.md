---
icon: assets/steam.png
label: Setting Up Proton On Steam
description: This guide covers everything from installing Proton, testing different versions for compatibility, and troubleshooting common issues like black screens. Whether you're new to Proton or looking to optimize your gaming experience, this step-by-step tutorial will help you get the most out of your Steam library on Linux.
layout: defualt

tags: [linux, proton, guide, dreaminal, setup, install]

expanded: true
visibility: public
templating: false
---

# Setting Up Proton On Steam

![Dreaminal Logo](assets/Dreaminal.png)

## How to Install Proton

1. Open **Steam** and go to **Settings**.
2. In the **Settings** menu, select **Steam Play** from the sidebar.
3. Check the box labeled **Enable Steam Play for supported titles**. 
4. (Optional) To enable Proton for all games, check **Enable Steam Play for all other titles**.
5. From the **Run other titles with** dropdown, select the desired version of Proton.
6. Click **OK** and restart Steam to apply changes.

## Testing Different Versions of Proton

1. Open your **Steam Library**.
2. Right-click on the game you want to test, then select **Properties**.
3. Go to the **Compatibility** tab.
4. Check **Force the use of a specific Steam Play compatibility tool**.
5. Select different Proton versions from the dropdown list and test each to find the best-performing version for your game.
6. Launch the game after each change to evaluate compatibility.

## Why Does the Game Go Black?

A black screen during game startup can result from a compatibility issue with the Proton version or graphics settings. Try the following troubleshooting steps:

1. **Switch Proton Versions:** Try different versions in the Compatibility tab to find one that works better.
2. **Update Graphics Drivers:** Make sure your graphics drivers are up to date.
3. **Lower Graphics Settings:** Some games may need lower settings to run smoothly on Proton.
4. **Launch Options:** Right-click the game in your Library, select **Properties**, and go to **Launch Options**. You can try adding options like `PROTON_USE_WINED3D=1` to resolve compatibility issues.
5. **Verify Game Files:** From the **Properties** menu, go to **Local Files** > **Verify integrity of game files** to ensure there are no missing or corrupt files.

If problems persist, check the ProtonDB community for other users' solutions for specific games.