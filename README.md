# Adding custom operations with files and directories via 7zip for Windows

Originally 7zip does not allow to easily move folder or file to archive from Explorer.
This patch to registry lets you do it (and whatever you want more)

* you can choose any text for menu label (for me it is "Move To 7z archive with maximum (7) level compression")
* you can choose different compression level (for me it is maximum (7) with option -mx7) etc
* you can add more commands with different labels and options (for me it is enough)
* commands may be added to Directory registry key (for folders) and to * key for files
