# subberthehut
subberthehut is a command-line based OpenSubtitles.org downloader, written in C.

It is inspired by [subdl](http://code.google.com/p/subdl/), which is not developed anymore.
In contrast to subdl, subberthehut can also do a name-based subtitle search in case the hash-based search returns no results.

### Dependencies
- xmlrpc-c
- glib2
- zlib
- bash-completion (make only)

### Installation and Usage
    $ make
    $ sudo make install

Then use ```subberthehut --help``` for usage information.

#### Arch Linux Package
subberthehut is available in the Arch User Repository (AUR):

https://aur.archlinux.org/packages/subberthehut/
