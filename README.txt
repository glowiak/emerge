Emerge - New generation ports-managing tool for FreeBSD inspired by Gentoo Linux.


Usage: emerge <package>
or: emerge <option> <package>

Options:
--sync                    Sync Ports Tree
--unmerge <package>       Remove a package
--search <package>        Search for a package

Dependiences:
-wget
-bash

Installing:
Exec this commands as root with installed dependiences:
# cd /usr/local/bin
# wget --no-check-certificate http://github.com/glowiak/emerge/raw/master/emerge
# chmod +x emerge
Or if You don't have wget:
# cd /usr/local/bin
# fetch --no-verify-peer http://github.com/glowiak/emerge/raw/master/emerge
# chmod +x emerge

!NOTE!: You must type 'emerge --sync' as root before using it!
