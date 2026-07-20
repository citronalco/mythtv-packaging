=====
MythTV distribution Packaging
=====

All directories contain scripts for building for the following distributions:
 - Ubuntu/Debian (.deb)
 - Fedora (.rpm)
 - Gentoo
 - OSX
 - Windows


====
Changes by Citronalco:
====

Only for building Ubuntu/Debian (.deb) packages:

Update MythWeb with some patches, and re-enable building MythWeb debian package.

Branches: fixes/34, fixes/35, fixes/36 

Included patches:
 - mythweb_fix_forget_old.patch: Fix clicking on "Forget old"
 - mythweb_fix_stoprecording.patch: Improve "Stop Recording"
 - mythweb_masterserverip.patch: Fix blank "Backend Status" page
 - mythweb_php_max_input_vars.patch: Move increasing PHP's max_input_vars to Apache2 config
 - mythweb_use_cdn_false.patch: Use local Javascript libraries by default instead of Google's CDN

For MythTV branches fixes/34 and fixes/35, EIT fixups for Vodafone Germany are backported (eitfixes_vodafone_germany_dvbc.patch)
