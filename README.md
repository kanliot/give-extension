# give-extension
Automatically give file extensions to files without them.  For Linux/BSD. 

I wrote this, because it seems like I had a bunch of downloads without file extensions.  That's all it does. It automaticaly rename files that do not have extensions, and skips files with recognized extensions. 

Installation is just downloading the single script, and running it like any other script with no dependencies.   It does require `xdg-open` and `python3 -m mimetypes`, which should be present on modern distros. 

### Examples
`$ give-extension file1 file2 file3`    
`$ give-extension user.download008478373 user.download8884884 cgi-bin?28883219`
