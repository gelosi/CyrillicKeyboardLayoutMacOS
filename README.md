# CyrillicKeyboardLayoutMacOS
Alternative to the flags, nice looking minimalistic keyboard layout for MacOS

Layouts are based on Russian - PC lauout. Because it's nicely mapped to the English (International!) and Cyrillic hardware keyboards. Therefore, primary actions are just like on the russian mac keyboard. Alt+ letter allows to have the rest of special cyrillic lettes from Ukrainian alphabet, for instance.

![GIF DEMO OF ICONS DARK THEME](https://j.gifs.com/r8NY2E.gif)


## How to install

You have to copy a bunle file from this repo into proper location on your mac, then this alternative layout will become available among the other sources in the Keyboard settings.


Here's locations you can use at step 3. of this manual:

alternative layout available only to yourself/current user: `~/Library/Keyboard Layouts/` \
alternative layout available to all: `/Library/Keyboard Layouts/` \
System Keyboards layout file (not recommended location!) `/System/Library/Keyboard Layouts/`


1. Open Finder
2. Press ⇧+⌘+G (Shift+Cmd+G) – this action will show a dialog where you can type direct location of the folder you want to go
3. Paste or type into that dialog window the following path: `~/Library/Keyboard Layouts`
4. You shoud have Finder window with the proper target location open at this moment
5. Copy the keyboard layout file to the recently opened folder
6. RESTART YOUR MAC (no kidding)
7. Do usual keyboard layout thing: go to the keyboard preferences, input sources, search for `Cyrillic` in the list of avaliable input languages – you should be able to find it, and you will recongize it immediately because of the icon `ї` :)

Done

### Contribution
Feel free to share your ideas / hacks regarding better use of keyboard! Also, if you like to customize & store your keyboard layout – I'll be happy to link your repo.

### References
##### Technical Note TN2056: Installable Keyboard Layouts
[Link to Apple Documentation](https://developer.apple.com/library/archive/technotes/tn2056/_index.html)
[Link to the hidden flag to support icon templates](https://github.com/tonsky/Universal-Layout/pull/22/files)
##### Human Interface Guidelines
[Custom Icons](https://developer.apple.com/design/human-interface-guidelines/macos/icons-and-images/custom-icons/) \
[Dark Mode](https://developer.apple.com/design/human-interface-guidelines/macos/visual-design/dark-mode/)

### Thanks!

Ukelete: a great helper tool to create custom layouts!
[Ukelete homepage](http://software.sil.org/ukelele/)

Dmitry Rodionov (@rodionovd): for help with the hidden config flags to support icon automatic color depending on theme (Light/Dark) 
