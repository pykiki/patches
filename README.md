# patches
Patches for everythings

# to apply the patch directly onto the directory
patch -d ./v4.9/ --dry-run -p 1 < ../patches/ureadahead-add-trace-event_ubuntu_4.9.patch
patch -d ./v4.9/ -p 1 < ../patches/ureadahead-add-trace-event_ubuntu_4.9.patch
