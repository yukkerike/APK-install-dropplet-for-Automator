# APK-install-dropplet-for-Automator

To download you may use git:
> $ git clone https://github.com/yukkerike/APK-install-dropplet-for-Automator.git

 or download a repo as zip.

To install - double click on a .workflow and select a folder. To work, adb needs to be installed in /usr/local/bin/ - via [brew](https://brew.sh): 

> $ brew cask install android-platform-tools 

or symlinked to the one in an Android SDK folder:

> $ ln -s ~/Library/Android/sdk/platform-tools/adb /usr/local/bin/adb

When everything's prepared, put .APKs in a dropplet and wait for the target dialog.

