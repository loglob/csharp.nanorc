# csharp.nanorc
Syntax highlighting for C# in GNU nano

## How to install
Choose either the csharp.nanorc or the csharp.colorful.nanorc file to install. Both contain highlighting for the same keywords, but the colorful file tries to give words with similar meanings similar colors whereas the default file just makes all regular keywords blue.

Copy your .nanorc file to */usr/share/nano/* to enable it for all users.
If you want to install it only for the current user, create or edit the *\~/.nanorc* file and add a line like this:
```
include "~/.nano/*.nanorc"
```
This will make nano use all .nanorc files found in *\~/.nano/* so copy the file to there.
