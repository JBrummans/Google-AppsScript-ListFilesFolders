# Google-AppsScript-ListFilesFolders
Google Appscript to list all files/folders within a given folder

Sourced from [here](https://ourtechroom.com/fix/list-all-googledrive-links-files-folder-to-googlesheet/)

Which author modified from [here](https://gist.github.com/abubelinha/c797c4b9c5f0da28e351de20ab7f433c)

Which was forked from [original upstream](https://gist.github.com/mesgarpour/07317e81e9ee2b3f1699)

Slight modification made to support Shared Drives as source code errored when reading file/folder owners.
Chose to use this version rather than the upstream due to its simplicity.

Add the code to a Google Sheet and reload the Spreadsheet. A new menu item will appear called `List Files/Folders`. When run, it prompts for a Google Drive ID location. Provide an ID and the script will wipe the current sheet and populate with the folders files and sub-folders. For shared drives ownership will be listed as `N/A`
