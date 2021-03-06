#### A dark skin for [Signal-Desktop](https://github.com/WhisperSystems/Signal-Desktop)
![Preview](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/img/screenshot.png)

###### Abandoned, Signal-Desktop has a dark theme now.

It also features some other minor alterations:
* Tighter look with less distance between elements
* Slightly smaller elements throughout
* Special styling of group administration messages
* Image view box appears at the bottom of the page (I find it jarring to switch to the top)


##### Installation
Installing the skin is easy – Just 2 steps!

1. Overwrite the CSS file by saving this [`manifest.css`](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/manifest.css) file in the following location (pick your OS):

 OS  | File Location
--- | -------------
Linux   | `~/.config/chromium/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.19.0_0/stylesheets/manifest.css`
Windows | `C:\Users\<Your_User_Name>\AppData\Local\Google\Chrome\User Data\Default\Extensions\bikioccmkafdpakkkcpdbppfkghcmihk\0.19.0_0\stylesheets\manifest.css`
Mac     | `~/Library/Application Support/Google/Chrome/Default/Extensions/bikioccmkafdpakkkcpdbppfkghcmihk/0.19.0_0/stylesheets/manifest.css`

 ![Save As](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/img/install.png)

1. Restart the Signal app through the menu

 ![Restart](https://raw.github.com/grandchild/Signal-Desktop-Darkskin/master/img/restart.png)


##### Uninstall
If you ever want to go back, simply repeat the install steps with the [original `manifest.css`](https://github.com/WhisperSystems/Signal-Desktop/raw/v0.19.0/stylesheets/manifest.css).


##### Updates
Every time chrome/ium updates your installation of Signal Desktop it will also replace the CSS file. You will then need to reinstall the Darkskin CSS. If there is an update to Signal Desktop and there happens to be no related [release](https://github.com/grandchild/Signal-Desktop-Darkskin/releases) yet, *please do open an issue about it, if there isn't one yet* and I will get to it.

While you wait, the previous CSS is still very likely to work, so try it.


##### Building
Install [`sass`](http://sass-lang.com/), and then from the base directory, run
```
sass stylesheets/manifest.scss manifest.css
```
