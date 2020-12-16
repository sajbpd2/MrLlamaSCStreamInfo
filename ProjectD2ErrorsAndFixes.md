##### Note: This list is not exhaustive and there are definitely unreported fixes to some of the complex issues. If none of these work, post in the [PD2 Discord #bug-chat](https://discord.gg/MgbKSmm6Mt).

| [****Issues****](#) |
| :-: |
| [Locked for illegal key](#how-to-fix-locked-for-illegal-key-error) |
| [Crash when pressing ESC](#how-to-fix-crash-when-pressing-esc-bug) |
| [VCRUNTIME140_1.dll / MSVCP140.DLL](#how-to-fix-vcruntime140_1dll-and-msvcp140dll-error) |
| [failed to load ProjectDiablo.dll](#how-to-fix-failed-to-load-projectdiablodll-error) |
| [failed to load game data files](#how-to-fix-failed-to-load-game-data-files-error) |
| [Bugged Launcher (White background)](#how-to-fix-bugged-launcher-with-white-background-error) |
| [UNHANDLED EXCEPTION c0000005](#how-to-fix-unhandled-exception-c0000005-error) |
| [Halt](#how-to-fix-halt-error) |
| [Silent Crash](#how-to-fix-silent-crash-error) |
| [d2data.mpq is corrupt / Empty OK Cancel box](#how-to-fix-d2datampq-is-corrupt-and-empty-ok-cancel-messagebox-error) |
| [Failed to Join Game](#how-to-fix-failed-to-join-game-error) |
| [Unable to Connect to Battle.net](#how-to-fix-unable-to-connect-to-battlenet-error) |
| [window resizing when joining a game](#how-to-fix-window-resizing-when-joining-a-game-bug) |
| [This app can't run on your PC](#how-to-fix-this-app-cant-run-on-your-pc-error) |
| [ultrawide monitor fix](#how-to-fix-the-aspect-ratio-on-ultrawide-monitors) |
| [can't gain experience](#how-to-fix-cant-gain-experience-bug) |
| [too high mouse sensitivity](#how-to-fix-too-high-mouse-sensitivity) |
| [can't teleport in Act 1 Cold Plains](#how-to-fix-cant-teleport-in-act-1-cold-plains) |
| [game minimizing on Alt+Tab](#how-to-fix-game-minimizing-on-alttab) |
| [mouse not working](#how-to-fix-mouse-isnt-working-in-the-main-menu-bug) |
| [launcher closing after clicking on PLAY](#how-to-fix-launcher-closing-after-clicking-on-play) |
| [unable to start correctly 0xc000007b](#how-to-fix-the-application-was-unable-to-start-correctly-0xc000007b-error) |
| [Cannot Create an Account](#how-to-fix-cannot-create-an-account-error) |
| [Wrong Password](#how-to-fix-wrong-password-error) |
| [CD-ROM](#how-to-fix-cd-rom-error) |

&nbsp;

&nbsp;

# How to Fix `Locked for illegal key` Error

You have been banned for using a stolen / pirated copy of diablo 2. To get your account unbanned please do the following:

&nbsp;

1. Purchase an official copy of Diablo 2 and Diablo 2 Lord of Destruction from https://www.blizzard.com/

2. Reinstall Project Diablo 2 using your legit version of Diablo 2

3. Log in to the server with your legit copy on a new account then message myself or a PD2 Moderator saying you have installed a proper copy and want to appeal your account lock for using a stolen key as well as provide your new account name and the account you wish to have unlocked

4. A Moderator will confirm you and your account will be unbanned in the unban wave that will take place 3 days from now

&nbsp;

&nbsp;

# How to Fix Crash when pressing ESC bug

- Open the `Settings` menu, go to `Stash` and uncheck `Export On Meno`

&nbsp;

&nbsp;

# How to Fix `VCRUNTIME140_1.DLL` and `MSVCP140.DLL` Error

- You are missing the Redistributable needed. [Click here to download the x64 Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe) and then install it.

&nbsp;

&nbsp;

# How to Fix `Failed to load ProjectDiablo.dll` Error

- You might be missing the x86 Redistributable. [Click here to download the x86 Redistributable](https://aka.ms/vs/16/release/vc_redist.x86.exe), install it and check if the game is working now.
- If the problem wasn't solved then check your anti-virus and restore the file.

&nbsp;

&nbsp;

# How to Fix `Failed to load game data files` Error

- You installed PD2 into the wrong folder, you must select your Diablo II: LoD folder in the PD2 installer.

Note: If you don't know where your Diablo II: LoD folder is then right click the Diablo II: LoD shortcut on your desktop and select `Open File location`. This is the folder that you need to select inside of the PD2 installer.

&nbsp;

&nbsp;

# How to Fix Bugged Launcher With White Background Error

- Run the Launcher as Administrator.

Note: Do not run the launcher multiple times, you can only have one instance of it running at a time.

&nbsp;

&nbsp;

# How to Fix Silent Crash Error

## Context: Interacting with items, skills, or monsters.

- Diablo 2 must be installed in English. Any other language will cause completely random crashes with items, skills, and monsters.
	- Link to English [Classic](https://www.blizzard.com/download/confirmation?platform=windows&locale=en_US&product=d2) and [LOD](https://www.blizzard.com/download/confirmation?platform=windows&locale=en_US&product=d2lod) installers. May need to sign in.
- If English Diablo II, re-install.
- Hovering over the bottom right of the stash is a known crash bug. No fix. Avoid moving your cursor to the bottom right of the stash.

&nbsp;

&nbsp;

# How to Fix "d2data.mpq is corrupt" and Empty OK Cancel Messagebox Error

### Solution 1: Rerun the `FIX_MPQS_RUN_AS_ADMIN.bat`
Open your ProjectD2 folder and browse to the MPQFixer folder. Run `FIX_MPQS_RUN_AS_ADMIN.bat` as admin and now try to start the game again.

### Solution 2: Manually deleting the (attributes) files
1. First, you will need [Ladik Zezula's MPQ Editor](http://www.zezula.net/en/mpq/download.html). Other MPQ editors usually can't open d2sfx.mpq or can't delete the (attributes) files.
2. Click on the `Open MPQ(s)` icon on the top left of the window.
3. Navigate to your Diablo II: LoD installation and select `d2data.mpq`, `d2char.mpq` and `d2sfx.mpq`. You can select them all at once by hoding Ctrl and clicking on each one.
4. Once you click `Open`, a window will popup. Just click `OK`. You will then see the 3 archives on the left side of the window.
5. Select one of them and then click on `Configure (attributes)` on the top right of the window.
6. Uncheck everything and click `OK`.
7. Repeat steps 6 and 7 for the other 2 archives.
8. Close the MPQ Editor and start the game again.

### Solution 3: Download the original MPQs
Get the original MPQs from the older installers. Install Diablo 2 using the provided legacy installer links and install PD2 into the new install.
- [Google Drive](https://drive.google.com/file/d/0BwtmRlAuN2x8X2FoWmhoR2pWQ2s/view)
- [OneDrive](https://onedrive.live.com/redir?resid=C9512C8BBA34920C!1795&authkey=!AHKYNghIssoWWVs&ithint=file%2czip)
- [Mediafire](http://www.mediafire.com/file/51r3c5s6hezsruz/DiabloII_113c_Installer.zip/file)
- [Torrent](https://cdn.discordapp.com/attachments/157962768534863872/160784109642186753/DiabloII_113c_Installer.zip.torrent)
- [Mega.nz](https://mega.nz/#!e9thyD6A!ExGJuZUtvRJ2c8DrxSL0ihCouh-ARbdVxODXIqVt3dc)

&nbsp;

&nbsp;

# How to Fix mouse isn't working in the main menu bug

- Open `UI.ini` inside of your ProjectD2 folder and set `Minimized=1`

&nbsp;

&nbsp;

# How to Fix launcher closing after clicking on PLAY

- Check your security programs and make sure nothing is blocking the launcher (Avast is known to cause this issue)

&nbsp;

&nbsp;

# How to Fix the aspect ratio on ultrawide monitors

- Open `ddraw.ini` inside of your ProjectD2 folder and set `maintas=true`

&nbsp;

&nbsp;

# How to Fix window resizing when joining a game bug

- [Download ddraw.ini](https://github.com/FunkyFr3sh/MrLlamaSCStreamInfo/releases/download/1/ddraw.ini) and place it into your ProjectD2 folder (replace existing file). Start the launcher and disable `Windowed Mode (-W)`.

Note: You can resize your window now by hovering over the window border and drag it. Use `Ctrl+Tab` or `RightAlt+RightCtrl` to unlock your cursor from the window.

&nbsp;

&nbsp;

# How to Fix `This app can't run on your PC` Error

- You're running a 32bit version of windows, PD2 doesn't support 32bit windows currently. Redownload the PD2 installer in a week or two and try again.

&nbsp;

&nbsp;

# How to Fix can't gain experience bug

- You must create a ladder character.

&nbsp;

&nbsp;

# How to Fix too high mouse sensitivity

- Open `ddraw.ini` inside of your ProjectD2 folder and set `adjmouse=true`.

Note: This fix will only work for fullscreen, if you want to adjust the mouse sensitivity in windowed mode you will have to use the ddraw windowed mode instead. To enable the ddraw windowed mode check: [window resizing when joining a game](#how-to-fix-window-resizing-when-joining-a-game-bug) 

&nbsp;

&nbsp;

# How to Fix can't teleport in Act 1 Cold Plains

- This is not a bug, it's a feature! You can find more info here: https://projectdiablo2.miraheze.org/wiki/Monsters

&nbsp;

&nbsp;

# How to Fix game minimizing on Alt+Tab

- `Alt+Enter` will disable windowed-fullscreen, just press it again to re-enable it.

&nbsp;

&nbsp;

# How to Fix `UNHANDLED EXCEPTION c0000005` Error

## Context: You travel to a new Act in-game.

- Disable "-ns" in the launcher.

&nbsp;

## Context: Hovering over item or skill descriptions.

- You have a non-English Diablo II installation. Must be English Diablo II.
- If English Diablo II, re-install.

&nbsp;

## Context: Killed Ventar the Unholy in Baal's fourth wave.

- I have yet to figure out why this happens. Other fixes have not seemed to help this issue. Usually not related to language or locale. Perhaps an issue with non-English Windows? Issue not solved, sorry.

&nbsp;

## Context: Hovered Over Bottom Right of Stash

- No known fix. Just keep your cursor away from bottom right of stash.

&nbsp;

## Context: You press `Play` on the Launcher and you receive the error.

### Possibility 1: Your PC just needs a full restart. Restart it.

### Possibility 2: You need to update your Vanilla client to 1.14d and then restart your PC afterwards.

#### Not sure what triggers this bug, but patching the Vanilla client from 1.14b to 1.14d reportedly fixes this issue for some. PC restart required to see if fix worked.

### Possibility 3: Compatibility

#### Sometimes Diablo 2 just isn't nice, especially if you're installing into a Diablo 2 version that is lower than 1.14.

1. For `Game.exe` in the `ProjectD2` folder, go to its properties and set the compatibility mode to `Windows XP SP2` or `Windows XP SP3`.
2. For both `Game.exe` and `PD2Launcher.exe` in the `ProjectD2` folder, go to their properties and set both of them to `Run as admininstrator`.

### Possibility 4: Cinematics Bug

#### PD2 reintroduced the old Cinematics bug where if your game client has no sound (usually through `-ns`), you crash on cinematics, including the intro cinematics.

- **If you do not have sound, get sound. If you do not want sound, simply turn down the audio in-game. You can mute the main menu with `Ctrl + M`.**

### Possibility 5: Bad Diablo II Install

- **Try launching Vanilla (unmodded) Diablo 2. If you get the error there, do a fresh re-install. If you don't, click on Battle.net to ensure you have the latest version. Then try launching PD2 again.**

### Possibility 6: Non-English Diablo 2 Install

#### This crash happens randomly when interacting with certain items, skills, and monsters.

- Diablo 2 must be installed in English. Any other language will cause completely random crashes with items, skills, and monsters.
	- Link to English [Classic](https://www.blizzard.com/download/confirmation?platform=windows&locale=en_US&product=d2) and [LOD](https://www.blizzard.com/download/confirmation?platform=windows&locale=en_US&product=d2lod) installers. May need to sign in.
- If English Diablo II, re-install.

&nbsp;

&nbsp;

# How to Fix Halt Error

## Context: Game doesn't start (line #378 / error ****5698)

- You must install the Lord of Destruction expansion. If you have multiple Diablo 2 installations then make sure you install PD2 into the correct folder that contains the Lord of Destruction expansion.

&nbsp;

## Context: Game doesn't start (line #3533 / error ****b317)

- Some of your original Diablo 2 LoD files are either corrupt or missing. Please reinstall Diablo 2 LoD.

Note: Do not move files around manually, make sure you are always using the PD2 installer to install PD2.

&nbsp;

## Context: Crash in main menu (line #677 / error ****8145)

- Disable `Windowed Mode (-W)` in the launcher and play in fullscreen or alternatively you can also use the ddraw windowed mode instead. To enable the ddraw windowed mode check: [window resizing when joining a game](#how-to-fix-window-resizing-when-joining-a-game-bug) 

&nbsp;

## Context: Character creates or joins a game.

- If you are able to create a new character and join a game but cannot join a game with an existing character because your game crashes with a Halt error, your character may have been corrupted somehow. This is not proven, waiting may simply fix it. I would be worried though, especially if it's online.
- If creating a new character still gives you a Halt error, then you likely have a bad install.
	- Be sure your game is a completely fresh install. You cannot copy and paste. You cannot re-use files from a previously modded install. Install Diablo II and then LOD and then PD2 all into the same folder.

&nbsp;

&nbsp;

# How to Fix `The Application was unable to start correctly (0xc000007b)` Error

- You might be missing the Redistributable needed. [Click here to download the x64 Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe) and then install it. If it was already installed then select Repair.

&nbsp;

&nbsp;

# How to Fix `Unable to Connect to Battle.net` Error

## Context: You entered a wrong password multiple times

- Wait a few minutes and then try to connect again.

&nbsp;

## Context: The game is showing the original background, not the PD2 Background

1. Press the Windows button and R at the same time (launch `Run.exe`).
2. Type `regedit` and press `OK`.
3. Navigate to `HKEY_CURRENT_USER\SOFTWARE\Blizzard Entertainment\Diablo II`.
4. Double click on the key `InstallPath`.
5. Set the `Value data` to your D2 folder (not your PD2 folder).
	- If your path ends in `...\ProjectD2`, delete that part.

&nbsp;

Note: The server might just be down currently, make sure you check the `#announcements` channel on discord for more info.

&nbsp;

&nbsp;

# How to Fix `Failed to Join Game` Error

- The game server you were in crashed. The realm server still thinks your character is in-game because the game server did not report you leaving the game since it crashed. Therefore, the realm doesn't let your character into another game. The only fix is to wait for the game server to restart and let your character out of the void. Patience. It could be 5 minutes or 24 hours.

&nbsp;

&nbsp;

# How to Fix `Cannot Create an Account` Error

#### No matter what random string of text you try, all accounts cannot be made.

- This is because you cannot use the D2 client to make an account. You need to [make an account on the website](https://www.projectdiablo2.com/authentication/login). The Game Account you provide is your in-game account name and password. If you aren't sure if you are typing it correctly, [check here](https://www.projectdiablo2.com/pd2accountmanagement). This will tell you your account but not your password. If you lost your password, as of now you are out of luck. Simply make a new account until they implement password resetting.

&nbsp;

&nbsp;

# How to Fix `Wrong Password` Error

#### This is a manifest of other issues.

[Try the Cannot Create an Account fix](#how-to-fix-cannot-create-an-account-error)

&nbsp;

&nbsp;

# How to Fix CD-ROM Error

- You need [VC 2010 SP1 x86](https://www.microsoft.com/en-US/download/confirmation.aspx?id=8328). Run it then restart your PC.
