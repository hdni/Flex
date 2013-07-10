# Flex
A GNOME 3.8 theme for GNOME Shell, GTK 3, Mutter, and Firefox.

## Installation
### GNOME Shell, GTK 3, Mutter
* Put the entire repository in `/usr/share/themes/`
* You can then use the Tweak Tool to set the themes.
* It is safe to remove the firefox.css files from the directory.

### Firefox
* Install the [Stylish](https://addons.mozilla.org/en-US/firefox/addon/stylish/) extension.
* Install the [FXChrome](https://addons.mozilla.org/en-US/firefox/addon/fxchrome/) theme.
* Go to your [Add-ons Manager](about:addons), select the User Styles page and then write a new style.
* Give the style a name and paste the contents of firefox.css.
* You will need to set to tabs to be on the bottom. To do so, set browser.tabs.onTop to "false" in [about:config](about:config).
* This style works well with the [Movable Firefox Button](https://addons.mozilla.org/en-us/firefox/addon/movable-firefox-button/), [Favicon Restorer](https://addons.mozilla.org/en-us/firefox/addon/favicon-restorer/?src=search), and [Hide Tabbar](https://addons.mozilla.org/en-us/firefox/addon/hide-tabbar/?src=ss) extensions.

## Notes
* This theme is not complete yet, and still has bugs. If you find any, please use the issues tracker!
* A very slightly modified version of Adwaita is included as GTK 2 theme, to avoid the default fallback. A GTK 2 theme will be made... eventually.
* The GNOME Shell theme uses Helvetica Neue. If you do not have it installed, it will use Arimo as fallback; you can get the font [here](https://www.google.com/fonts/download?kit=32ci3aiii8TFh9L2O_kK1w). You can also change the font to your liking in the `gnome-shell.css` file.
