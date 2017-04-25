# Note
At least for the Steam version,
Emily is Away has different file formats for Windows, Linux, and OS X.

Instead of attempting to create save files for all three operating systems,
and all possible routes, for now, this repo will just detail where to find
your save data. In all three cases, the save files are human editable.

# Directories

## Windows
Use `regedit` to modify values in `HKEY_CURRENT_USER\Software\Kyle Seeley\Emily Is Away`

## OS X
Run

`plutil -convert xml1 ~/Library/Preferences/unity.Kyle\ Seeley.Emily\ Is\ Away.plist`

to convert the file to an xml format, edit it with your text editor of choice, then run

`plutil -convert binary1 ~/Library/Preferences/unity.Kyle\ Seeley.Emily\ Is\ Away.plist`

## Linux
Edit `~/.config/unity3d/Kyle\ Seeley/Emily\ Is\ Away/prefs`
