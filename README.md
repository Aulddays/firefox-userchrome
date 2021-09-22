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
