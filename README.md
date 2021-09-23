# firefox-userchrome
Style firefox

## Usage

### Locate firefox user profile
* Firefox menu -> Help -> More Troubleshooting Information
* Search for "Profile Folder"
* Click "Open Folder"

### Check out *userChrome.css* file
Put userChrome.css file in a folder named *chrome* in Firefox Profile Folder.

For example, if Profile Folder is
> C:\Users\Aulddays\Firefox

then *userChrome.css* should be in
> C:\Users\Aulddays\Firefox\chrome\userChrome.css

### Enable *userChrome.css*
* Goto about:config
* Set **toolkit.legacyUserProfileCustomizations.stylesheets** to **true**

### Tip: Inspect the Firefox browser chrome
* Open `Developer Tools` by pressing *F12*
* In *Settings* of *Developer Tools*, enable:
  * Enable browser chrome and add-on debuggint toolboxes
  * Enable remote debugging
* Firefox menu -> More Tools -> Brwoser Toolbox, or press `Ctrl-Shift-Alt-I`
