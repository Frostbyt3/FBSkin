# FBSkin
FBSkin is a Steam skin based on Windows 10's Metro with a flair!

### Customization
For Millennium, use the respective tabs under the theme's settings.

For SFP, you may edit the config in `~/config/options.json` to dynamically patch in options for the skin! Please reference the values in `~/skin.json` for now to know what they do. The skin folder must be named `FBSkin` for this to work at the present time!

#### Colorization
You can colorize both the foreground and background colors of FBSkin!

For Millennium, under the `Theme` tab, enable your choice of foreground and/or background blending. Optionally, set the blend amount and color space (different approaches to blending that produces different results). Under the `Colors` tab, choose the colors for blending and you've got a whole new look!

For SFP, edit the config in `~/config/options.json`!

#### Features
On Windows, the accent color will take your system's accent color by default. If you are on a system that does not support this variable, there is a fallback value. If you wish to change this, please manually enter the value in `~/config/theme/mode/<theme>/colors.css`.

FBSkin features several added buttons for an improved experience:
* The library window's menu button toggles the visibility of the root menu bar and the navigation menu bar.
* You can toggle the visibility of the current user container on the friends window using the navigation button in the upper-left corner.
* The library sidebar can be toggled by an added button. You will find this button on the sidebar when opened and in the bottom-right corner when closed while the window is focused and hovered.
* The game page details panel is hidden by default. A button has been added to the playbar to toggle it.
* The game event and community content feeds can be toggled, with the event feed displayed by default. The button is also in the playbar.

#### Installation
1. Download your preferred version.
2. Extract the archive `FBSkin`.
3. Navigate to your Steam folder.
4. Place the extracted skin folder in `~/steamui/skins`.
5. Enable JavaScript support in your patcher of choice.
6. Select the skin in the patcher.