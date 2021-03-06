All your audio books in one place! Cozy is an audio book player which let's you manage and play back your collection.

![Screenshot](https://raw.githubusercontent.com/geigi/cozy/img/img/screenshot.png)

# Features:
- **Import** all your audio books into Cozy to browse them comfortably
- **Sort** your audio books by author, reader & name
- **Remembers** your **playback position**
- **Sleep timer**
- **Playback speed control**
- **Search** your library
- **Offline Mode!** This allows you to keep an audio book on your internal storage if you store your audiobooks on an external or network drive. Perfect to listen on the go!
- Add **mulitple storage locations**
- **Drag & Drop** to import new audio books
- Support for DRM free **mp3, m4a (aac, ALAC, ...), flac, ogg, wav** files
- Mpris integration (**Media keys** & playback info for desktop environment)
- Developed on Fedora and tested under elementaryOS

# How can I get it?
## Flatpak
For most distributions you can use Flatpak to install and run Cozy: <a href="https://flathub.org/repo/appstream/com.github.geigi.cozy.flatpakref">Flathub</a>

Or use the following commands:
```
flatpak remote-add --user --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install --user flathub com.github.geigi.cozy
```

## elementaryOS
If you're running elementaryOS, you can get Cozy from the <a href="https://appcenter.elementary.io/com.github.geigi.cozy">App Center</a>.

## Arch Linux
Arch Linux users can find Cozy under the name `cozy-audiobooks` in the AUR:
```
$ pacaur -S cozy-audiobooks
```

## Ubuntu, Debian, openSUSE, Fedora repositories
If you prefer a custom repository - for Ubuntu, Debian, openSUSE and Fedora there are package repositories on the <a href="https://software.opensuse.org//download.html?project=home%3Ageigi&package=com.github.geigi.cozy">openSUSE Build Service</a>.

If you like this project, consider supporting me on <a href="https://www.patreon.com/bePatron?u=8147127"> Patreon</a> :)

# Changelog
## 0.6.0
- **Offline Mode!** If your audiobooks are on an external or network drive, you can switch the download button to keep a local cached copy of the book to listen to on the go. To enable this feature you have to set your storage location to external in the settings.
-  Detect online/offline storage devices
-  Option to hide unavailable books
-  Support for **wav** files
-  Support for audio files that have no tags at all
-  You can mark books as read using the right click menu
-  New setting: Prefer cover image file over embedded covers
-  Redesigned Sleep Timer
-  More Sleep Timer: You can now stop the playback after the current chapter
-  And even more: Fadeout on timer end (in settings)
-  Redesigned hello screen and settings
-  Fixed bug where cozy would not start on GTK < 3.22
-  If no author field is present, the reader field will be used as author. This requires a force reimport (settings) on already imported books.
- Optimizations under the hood


# Q&A
## I can't uninstall the Flatpak:

Try
```
flatpak uninstall com.github.geigi.cozy/x86_64/stable
```
or
```
flatpak uninstall --user com.github.geigi.cozy/x86_64/stable
```
Thanks to @Meresmata

# Help me translate cozy!
Cozy is on <a href="https://www.transifex.com/geigi/cozy/"> Transifex</a>, where anyone can contribute and translate. Can't find your language in the list? Let me know!

# A big thanks
To the creators from <a href="https://wiki.gnome.org/Apps/Lollypop">Lollypop</a>. Their code helped a lot to learn Python and GTK development.

To the contributors on GitHub:
- oleg-krv 
- AsavarTzeth
- worldofpeace
- camellan
- jnbr

The translators:
- camellan
- Vistaus
- Distil62
- karaagac
- HansCz
- mvainola
- giuscasula
- abuyop
- akodi
- cleitonjfloss
- amadeussss
- nvivant
- Foxyriot
- mardojai
- trampover

To nedrichards for the Flatpak.