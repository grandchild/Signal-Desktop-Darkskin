#### A dark skin for [Signal-Desktop](https://github.com/WhisperSystems/Signal-Desktop)
![Preview](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/screenshot.png)

##### Installation
Simply overwrite the CSS file of the app with the `manifest.css` from here.

OS  | File Location
--- | -------------
Linux   | `~/.config/chromium/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.7.0_0/stylesheets/manifest.css`
Windows | `C:\Users\<Your_User_Name>\AppData\Local\Google\Chrome\User Data\Default\Extensions\bikioccmkafdpakkkcpdbppfkghcmihk\0.7.0_0\stylesheets\manifest.css`
Mac     | `~/Library/Application Support/Google/Chrome/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.7.0_0/stylesheets/manifest.css`

##### Building
Run
```
sass stylesheets/manifest.scss manifest.css
```