#### A dark skin for [Signal-Desktop](https://github.com/WhisperSystems/Signal-Desktop)
![Preview](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/screenshot.png)

##### Installation
Simply overwrite the CSS file of the app with the `manifest.css` from here.

OS  | File Location
--- | -------------
Linux   | `~/.config/chromium/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.8.0_0/stylesheets/manifest.css`
Windows | `C:\Users\<Your_User_Name>\AppData\Local\Google\Chrome\User Data\Default\Extensions\bikioccmkafdpakkkcpdbppfkghcmihk\0.8.0_0\stylesheets\manifest.css`
Mac     | `~/Library/Application Support/Google/Chrome/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.8.0_0/stylesheets/manifest.css`

##### Updates
Everytime chrome/ium updates your installation of Signal Desktop it will also replace the CSS file. You will then need to reinstall the Darkskin CSS. If there is an update to Signal Desktop and there happens to be no related [release](https://github.com/grandchild/Signal-Desktop-Darkskin/releases) yet, *please do open an issue about it, if there isn't one yet* and I will get to it.

##### Building
Run
```
sass stylesheets/manifest.scss manifest.css
```
