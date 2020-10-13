Emerge - New generation ports-managing tool for FreeBSD inspired by Gentoo Linux.


Usage: emerge <package>
or: emerge <option> <package>

Options:
--sync                    Sync Ports Tree
--unmerge <package>       Remove a package
--search <package>        Search for a package

Dependiences:
-bash

Installing on FreeBSD:
Exec this commands as root with installed dependiences:
# cd /usr/local/bin
# fetch --no-verify-peer http://github.com/glowiak/emerge/raw/master/emerge
# chmod +x emerge

!NOTE!: You must type 'emerge --sync' as root before using it!

How to install depenciences:
FreeBSD: # pkg install bash
NetBSD: # pkgin install bash
OpenBSD: # pkg_add bash

Current version:
FreeBSD: 0.4
NetBSD: planned
OpenBSD: planned

I'm gonna make emerge for NetBSD and OpenBSD. Good idea?
