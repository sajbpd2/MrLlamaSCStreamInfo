##### Note: With continuing updates, prior knowledge to fixes are being lost and new ways have to be discovered. As such, it is quite likely that some of these fixes are outdated.

##### Note: This list is not exhaustive and there are definitely unreported fixes to some of the complex issues. If none of these work, post in the [PD2 Discord #bug-chat](https://discord.gg/MgbKSmm6Mt).

| [****Issues****](#) |
| :-: |
| [d2data.mpq is corrupt](#how-to-fix-d2datampq-is-corrupt-error) |
| [c0000005](#how-to-fix-c0000005-error) |
| [mouse not working](#how-to-fix-mouse-not-working) |
| [window resizing when joining a game](#how-to-fix-window-resizing-when-joining-a-game) |
| [launcher closing after clicking on PLAY](#how-to-fix-launcher-closing-after-clicking-on-play) |
| [Halt](#how-to-fix-halt-error) |
| [VCRUNTIME140_1.dll](#how-to-fix-vcruntime140_1dll-error) |
| [Silent Crash](#how-to-fix-silent-crash-error) |
| [Bugged Launcher](#how-to-fix-bugged-launcher-with-white-background-error) |
| [Unable to Connect to Battle.net](#how-to-fix-unable-to-connect-to-battlenet-error) |
| [Failed to Join Game](#how-to-fix-failed-to-join-game-error) |
| [Cannot Create an Account](#how-to-fix-cannot-create-an-account-error) |
| [Wrong Password](#how-to-fix-wrong-password-error) |
| [CD-ROM](#how-to-fix-cd-rom-error) |

# How to Fix "d2data.mpq is corrupt" Error

Open your ProjectD2 folder and browse to the MPQFixer folder. Run "FIX_MPQS_RUN_AS_ADMIN.bat" as admin and now try to start the game again. If it still doesn't work, try this:

Get the original MPQs from the older installers. Install Diablo 2 using the provided legacy installer links and install PD2 into the new install.
- [Google Drive](https://drive.google.com/file/d/0BwtmRlAuN2x8X2FoWmhoR2pWQ2s/view)
- [OneDrive](https://onedrive.live.com/redir?resid=C9512C8BBA34920C!1795&authkey=!AHKYNghIssoWWVs&ithint=file%2czip)
- [Mediafire](http://www.mediafire.com/file/51r3c5s6hezsruz/DiabloII_113c_Installer.zip/file)
- [Torrent](https://cdn.discordapp.com/attachments/157962768534863872/160784109642186753/DiabloII_113c_Installer.zip.torrent)
- [Mega.nz](https://mega.nz/#!e9thyD6A!ExGJuZUtvRJ2c8DrxSL0ihCouh-ARbdVxODXIqVt3dc)

# How to fix mouse not working

- Open UI.ini with notepad and set "Minimized" to "1"

# How to fix launcher closing after clicking on PLAY

- Check your security programs and make sure nothing is blocking the launcher (Avast is known to cause this issue)

# How to fix window resizing when joining a game

- Download [ddraw.ini](https://github.com/FunkyFr3sh/MrLlamaSCStreamInfo/blob/master/ddraw.ini) and place it into your PD2 folder (replace existing file). Start the launcher and disable Windowed mode "-W".

# How to Fix c0000005 Error

## Context: You travel to a new Act in-game.

- Disable "-ns" in the launcher.

## Context: Hovering over item or skill descriptions.

- You have a non-English Diablo II installation. Must be English Diablo II.
- If English Diablo II, re-install.

## Context: Killed Ventar the Unholy in Baal's fourth wave.

- I have yet to figure out why this happens. Other fixes have not seemed to help this issue. Usually not related to language or locale. Perhaps an issue with non-English Windows? Issue not solved, sorry.

## Context: Hovered Over Bottom Right of Stash

- No known fix. Just keep your cursor away from bottom right of stash.

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

# How to Fix Halt Error

## Context: Character creates or joins a game.

- If you are able to create a new character and join a game but cannot join a game with an existing character because your game crashes with a Halt error, your character may have been corrupted somehow. This is not proven, waiting may simply fix it. I would be worried though, especially if it's online.
- If creating a new character still gives you a Halt error, then you likely have a bad install.
	- Be sure your game is a completely fresh install. You cannot copy and paste. You cannot re-use files from a previously modded install. Install Diablo II and then LOD and then PD2 all into the same folder.

# How to Fix `VCRUNTIME140_1.DLL` Error

- You are missing the Redistributables needed. You need both [x86](https://aka.ms/vs/16/release/vc_redist.x86.exe) and [x64](https://aka.ms/vs/16/release/vc_redist.x64.exe). Run them.

# How to Fix Silent Crash Error

## Context: Interacting with items, skills, or monsters.

- Diablo 2 must be installed in English. Any other language will cause completely random crashes with items, skills, and monsters.
	- Link to English [Classic](https://www.blizzard.com/download/confirmation?platform=windows&locale=en_US&product=d2) and [LOD](https://www.blizzard.com/download/confirmation?platform=windows&locale=en_US&product=d2lod) installers. May need to sign in.
- If English Diablo II, re-install.
- Hovering over the bottom right of the stash is a known crash bug. No fix. Avoid moving your cursor to the bottom right of the stash.

# How to Fix Bugged Launcher With White Background Error

- Run the Launcher as Administrator.

# How to Fix `Unable to Connect to Battle.net` Error

## Context: You entered a wrong password multiple times

- Wait a few minutes and then try to connect again.

## Context: The game is showing the original background, not the PD2 Background

1. Press the Windows button and R at the same time (launch `Run.exe`).
2. Type `regedit` and press `OK`.
3. Navigate to `HKEY_CURRENT_USER\SOFTWARE\Blizzard Entertainment\Diablo II`.
4. Double click on the key `InstallPath`.
5. Set the `Value data` to your D2 folder (not your PD2 folder).
	- If your path ends in `...\ProjectD2`, delete that part.

# How to Fix `Failed to Join Game` Error

- The game server you were in crashed. The realm server still thinks your character is in-game because the game server did not report you leaving the game since it crashed. Therefore, the realm doesn't let your character into another game. The only fix is to wait for the game server to restart and let your character out of the void. Patience. It could be 5 minutes or 24 hours.

# How to Fix `Cannot Create an Account` Error

#### No matter what random string of text you try, all accounts cannot be made.

- This is because you cannot use the D2 client to make an account. You need to [make an account on the website](https://www.projectdiablo2.com/authentication/login). The Game Account you provide is your in-game account name and password. If you aren't sure if you are typing it correctly, [check here](https://www.projectdiablo2.com/pd2accountmanagement). This will tell you your account but not your password. If you lost your password, as of now you are out of luck. Simply make a new account until they implement password resetting.

# How to Fix `Wrong Password` Error

#### This is a manifest of other issues.

[Try the Cannot Create an Account fix](#how-to-fix-cannot-create-an-account-error)

# How to Fix CD-ROM Error

- You need [VC 2010 SP1 x86](https://www.microsoft.com/en-US/download/confirmation.aspx?id=8328). Run it then restart your PC.
