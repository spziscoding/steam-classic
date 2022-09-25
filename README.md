# Green Classic skin for Steam chat and friends UI
This skin for the new chat and friends UI was created after Valve made it problematic to revert to the old-style windows. My quest was to make the new windows look as close as possible to those of the old flat classic green steam skin.

## Installation

### Windows

1. Extract the Classic folder from [classic_steam.zip](https://github.com/spziscoding/steam-classic/bloc/main/classic_steam.zip) to Steam/skins
2. Save the [friends.custom.css](https://github.com/spziscoding/steam-classic/bloc/main/friends.custom.css) file to your PC and put in your Steam\clientui\ folder.
3. [https://github.com/PhantomGamers/SFP/releases](Download) the latest patcher to allow for customization.
4. Launch the patcher and wait for it to apply the changes.
5. Restart Steam.

### Linux & Mac

1. Copy and add the [friends.custom.css](https://github.com/spziscoding/steam-classic/bloc/main/friends.custom.css) code to Steam/skins/Classic/resource/webkit.css
2. Search the file contents for Linux or Mac in any text editor.
3. Remove sections as instructed within the code.

## Uninstallation

### Windows

* Use the dedicated patcher button to clear the cache.
* Alternatively, ensure that Steam and the patcher tool are closed, then remove the %LOCALAPPDATA%\Steam\htmlcache\Cache\ folder.
* For purity, remove the Steam\clientui\css\ folder (and Steam\steamui\css\ if using the library skin) inside your Steam installation folder.

### Credits

* [PhantomGamers](https://github.com/PhantomGamers) for creating the tool that allows to apply skins, and for tips on managing the randomized class names.
* [RedSigma](https://github.com/redsigma) for creating a custom skin for the new chat, which I initially used as a template.
* [RoseTheFlower](https://github.com/RoseTheFlower) for creating a clean metro skin ui for the new chat, which I was inspired to recreate the green classic skin.
