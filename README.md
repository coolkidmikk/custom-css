#  Animated Custom CSS 
A minimal Firefox theme with a hidden URL bar.

https://github.com/user-attachments/assets/9795d141-8fb8-4281-a7f2-9b67df15193e

# Compatibility
This customization is designed specifically for Firefox and Librewolf. It is not compatible with Zen Browser.
# Installation
-  Open `about:config` in Firefox and set `toolkit.legacyUserProfileCustomizations.stylesheets` to true.
-  Navigate to `about:support` and locate the `Profile Directory` row. Copy the path provided.
-  Open your terminal, navigate to that directory, and clone this repository into a folder named `chrome`:
```bash
cd the/path/you/just/copied
git clone https://github.com/coolkidmikk/custom-css.git chrome
```
-  Hide the bookmarks toolbar by pressing Ctrl+Shift+B or right clicking and selecting "Never Show."
-  You MUST have to have this [Adaptive Tab Bar Color](https://addons.mozilla.org/en-US/firefox/addon/adaptive-tab-bar-colour) extension. Without this,
   the toolbar will remain transparent and difficult to read.
-  Optional Extension: Install [Fistome](https://addons.mozilla.org/en-US/firefox/addon/fistome) to match the homepage view shown in the preview video.   
-  Restart your browser for the theme to be applied.
#  UI Alignment and Balancing
If the URL bar or tabs appear shifted to one side, you must balance the toolbar layout manually:
-  Remove the Firefox View button from the top-left corner.
-  Ensure the search box is centered by placing an equal number of icons on both sides (e.g., 4 tools on the left and 4 on the right).
   Refer to this [example image](assets/example_image.png). for the ideal layout.

This project was fully inspired by [AnimatedFox](https://github.com/remyrf/AnimatedFox), which has since been archived.
Please note that this userChrome customization is complex and prone to breaking with new Firefox updates. While this theme is functional, it is not perfect and may contain minor bugs.

