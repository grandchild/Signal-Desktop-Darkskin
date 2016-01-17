#### A dark skin for [Signal-Desktop](https://github.com/WhisperSystems/Signal-Desktop)
![Preview](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/screenshot.png)

##### Installation
Either directly overwrite or just patch the CSS file at

OS  | File Location
--- | -------------
Linux   | `~/.config/chromium/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.1.9_0/stylesheets/manifest.css`
Windows | `C:\Users\<Your_User_Name>\AppData\Local\Google\Chrome\User Data\Default\Extensions\bikioccmkafdpakkkcpdbppfkghcmihk\0.1.9_0\stylesheets\manifest.css`
Mac     | `~/Library/Application Support/Google/Chrome/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.1.9_0/stylesheets/manifest.css`

In Linux, `cd` into the repository folder and run:
```bash
patch --dry-run <path-to-CSS-file> manifest.css.patch
patch -b <path-to-CSS-file> manifest.css.patch
```
