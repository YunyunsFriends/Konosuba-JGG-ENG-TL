![title](https://user-images.githubusercontent.com/110912092/230537187-15e17549-70ac-4be3-abc0-2edab3e9f6d5.png)
## Konosuba Judgment on this Greedy Game Prologue English Patch for PC & Switch Proof of Concept
This patch adds a English menu and translates all the prologue scripts on PC and Switch.
###
We are looking for translators to help translate the rest of the vn's scripts, and will not be able to finish the patch without them because we do not want to machine translate the entire game.
###
If you wish to help or interact with us please join our Discord server https://discord.gg/X2MWMUzWJ5 or contact Shaggy_thecat#3572.
## PC Patch Features
- Translated Menus and System text.
- A slightly modified font/text box to fit more text on screen.
- Enabled Debug Menu. ~(Mostly broken)~ Fix provided by nikvoid. Thank you!
- Reduced font size.
## Switch Patch
- The Switch patch is a partial conversion of the PC patch and will have non-working options exposed.
- The "Game Over" button will call a debug function to trip all the flags in the game. _(This can lead to spoilers.)_
- Reduced font size.
###
_You will need to have a Switch with [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) cfw to install the patch. Extract it to the root of your sd card._
## Vita Patch
- Contains 7 machine translated scripts. No textures or menus were edited.
- Reduced font size. _Note: Unlike PC and Switch the font on Vita has not been fixed. I.E some letters may be cut off on some edges._
## Where to buy the game
###
Windows: **[DMM DLSOFT](https://dlsoft.dmm.com/detail/images_0013/)**
- You need to use a vpn set to Japan to view and purchase the game due to the page being blocked outside of Japan.
###
Nintendo Switch: **[eShop](https://store-jp.nintendo.com/list/software/70010000035750.html)**
- You will need a Japanese eshop account to purchase the game.
## FAQ
### Do you plan to patch the Vita and PS4 versions?
If we get translators on board to help with this project yes. Those versions of the game have various differences that we would need to make adjustments for due to differences in textures and the resolution on Vita.
### Do I need the game?
Yes, the files in releases are what's strictly needed for the patch. If you try to run the executable in the patch files without overwriting the game files you will get a black screen. 
### Can I play this on a Steam Deck?
Yes, you will need to install **[GE-Proton](https://github.com/GloriousEggroll/proton-ge-custom)** using ProtonUp-Qt and add Konosuba: JGG to Steam and launch it. Then install this version of **[DirectX](https://lutris.net/files/tools/directx-2010.tar.gz)** to Konosuba: JGG's prefix using WineTrick's run exe on prefix feature.
## Credits & Thanks
### Cheese
- Texture Editing / Redrawing
- Proofreading
- Initial POC release on [Reddit](https://www.reddit.com/r/Konosuba/comments/10ic5hm/konosuba_vnjudgement_on_this_greedy_game_eng/)
### Goku
- Menu TL
### Shaggy
- Texture Adjustments / Remapping & Implementation
- Modding
### nikvoid / ErisOrder
- Provided tools (suba-yoku-dbg and konosuba-yokubukai)
- [Fixed](https://github.com/Shaggythecat/Konosuba-JGG-ENG-TL/issues/1) the debug menu.
- Patch loading change
### Hallows Eve / Slender ඩ
- Prologue Patch Playtesting
## Tools Used
### **[FreeMote Toolkit](https://github.com/UlyssesWu/FreeMote)**
- Unpack and Repack game PSBs and SCNs.
### **[suba-yoku-dbg](https://github.com/ErisOrder/suba-yoku-dbg)**
- Outputs debug information.
### **[konosuba-yokubukai](https://github.com/ErisOrder/konosuba-yokubukai)**
- A repo to assist translation K:JGG translation projects.
### **[VNTranslationTools](https://github.com/arcusmaximus/VNTranslationTools)**
- Exports and imports strings from .scn files to a speadsheet.
- Used to port edited strings from PC to Switch and Vita.
### **[ScnEditorGUI](https://github.com/hiroshiyuri/scn-editor-gui)**
- Edit .scn files.
### **[PlaMemo-Scenario-Parser](https://github.com/Rimi-kun/PlaMemo-Scenario-Parser)**
- Outputs a given script to a text file.
- Used earlier in the project but was replaced with VNTranslationTools.
## Disclaimers
This project is not associated with or endorsed by Kadokawa or MAGES./5pb.
