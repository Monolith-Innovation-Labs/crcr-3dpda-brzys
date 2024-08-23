# 3DPDA integration for Chernobyl Relay Chat Rebirth, maintained by Brzys
 Chernobyl Relay Chat Rebirth is an IRC-based chat app for Anomaly, originally developed by TKGP for CoC. Features an independent client as well as in-game chat, automatic death messages, and compatibility with all other add-ons.
 This mod integrates it into the Anomaly 3D PDA
![image](https://github.com/user-attachments/assets/cafbb53f-d92d-46a2-9971-b48194f3a03d)
![344320831-04b45b92-644e-4564-befc-dfd8aa57c8e3](https://github.com/user-attachments/assets/677e4de1-1713-43e4-b51f-fc65c104aa06)
## [Download](https://github.com/Monolith-Innovation-Labs/crcr-3dpda-brzys/releases)

## Note
This mod needs an EXE app provided by the original CRCR mod to run.

# Installation
1. Install the [.NET framework](https://www.microsoft.com/net/download/framework) if you don't have it already
2. Download the [CRCR by Brzys](https://github.com/8r2y5/Chernobyl-Relay-Chat-Rebirth)
3. Download the [3DPDA integration](https://github.com/Monolith-Innovation-Labs/crcr-3dpda-brzys/releases)
4. Extract the contents of CRCR.zip into  game directory
5. Extract the contents of 3DPA_integration_brzys.zip into  game directory
6. (Optional) Install the [Anomaly Mod Configuration Menu](https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-mod-configuration-menu) for advanced mod configuration

# Mod Manager
I will convert it to a text guide in the future
![image](https://github.com/user-attachments/assets/75fc3c60-2b64-4a1a-972e-f49d7f83f072)


# Compatibility with GAMMA
Gamma uses iTheon's PDA Taskboard, so CRCR will additionally need a patch to ensure compatibility with it (CRCR_iTheon_PDA_Taskboard_compatibility_patch.zip). Once you install it, CRCR should work without problems with the GAMMA mod pack.
 ![310261146-066d9fb0-41ab-4c5d-9ed2-59121a5b20bd](https://github.com/user-attachments/assets/d1471f42-c82e-4554-9bde-b0db762641d2)
# Compatibility with non-US keyboard layouts
Stalker reads the key position on the keyboard ([DIK](https://community.bistudio.com/wiki/DIK_KeyCodes)) rather than its value after being pressed. For example, when using AZERTY, you don't have to manually change W to Z; you simply press Z, and the game interprets it as W. However, a problem arises when typing in the chat. You need to specifically remember which character on your AZERTY keyboard corresponds to the QWERTY character.

This is not a problem anymore; install [MCM](https://www.moddb.com/mods/stalker-anomaly/addons/anomaly-mod-configuration-menu) and change the keyboard layout to one of the many available (currently 55). 

I don't promise that everything will work perfectly (Stalker in the English version doesn't support many characters, such as £, ń, ł, Æ, ř, etc.). Additionally, different languages have varying approaches to entering diacritical marks. Sometimes it's `AltGr + character`, sometimes `AltGr + number`, and the combinations can be different and sometimes quite complex ([look up how to type Czech characters with a háček XD](https://www.czechtime.cz/article/how-to-type-czech-characters-on-keyboard/)). I don't have the energy to implement this for all 55 supported languages, especially considering that most of the obtained characters are not supported in Stalker.

I tried to adjust the keys as best I could. However, if you think that any key could be assigned better or if there's a particular character missing, please create an issue or let me know on Discord (amon_de_shir). The layouts were generated by a script, so there's definitely room for improvement.

# Does it work with other PDA related mods?
If mod doesn't modify the `pda.set_active_subdialog` function, there shouldn't be any problem.

###  Incompatible Mods (Patch Required)
- [iTheon's PDA Taskboard](https://www.moddb.com/mods/stalker-anomaly/addons/itheons-pda-taskboard)

### Tested compatible mods:
- [Advanced map scale in the PDA](https://www.moddb.com/mods/stalker-anomaly/addons/advanced-map-scale-in-the-pda)
- [Better PDA Progression](https://www.moddb.com/mods/stalker-anomaly/addons/better-pda-progression)
- [[DLTX] Better hands position for PDA Reanimation](https://www.moddb.com/mods/stalker-anomaly/addons/dltx-better-hands-position-for-pda-reanimation)
- [PDA reanimation](https://www.moddb.com/mods/stalker-anomaly/addons/pda-reanimation)
- [PDA Hacking](https://www.moddb.com/mods/stalker-anomaly/addons/pda-hacking)

### Patches
[3D PDA CRCR iTheon PDA Taskboard compatibility patch](https://github.com/Monolith-Innovation-Labs/3d-crcr-itheon-pda-taskboard-compatibility-patch/)

# What's Planned  
- [x] New In-game chat GUI and (possibly) integrating it in Anomaly's 3D PDA
- [x] G.A.M.M.A modpack compatibility
- [x] Nick autocomplete

# My other mods
