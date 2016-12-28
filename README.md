## notessync
Applescript and plist to create files from Notes.

### Installation
`launchctl load org.jack.notessync.plist`

### Motivation

I wanted a way to have notes created on my phone (while on the go) to be automatically written to a folder on my computer. This solution utilizes iCloud sync for the Notes app to achieve the desired behavior - the only problem is that (AFAIK) the desktop Notes app needs to be open and in focus for the notes to sync from iCloud to the desktop.

### Other things to know
1. I couldn't get WatchPaths to work. Currently, this script is configured to kick off every 5 seconds
2. The script looks in folders named "Blog" and "Recently Deleted", and only writes out notes that begin with "Blog_"
