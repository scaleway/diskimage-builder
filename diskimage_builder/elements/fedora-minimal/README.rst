==============
fedora-minimal
==============
Create a minimal image based on Fedora.

Use of this element will require 'yum' and 'yum-utils' to be installed on
Ubuntu and Debian. Nothing additional is needed on Fedora or CentOS. The
element will need `python-lzma` everywhere.

Due to a bug in the released version of urlgrabber, on many systems an
installation of urlgrabber from git is required. The git repository
can be found here: http://yum.baseurl.org/gitweb?p=urlgrabber.git;a=summary

This element sets the ``DISTRO_NAME`` var to 'fedora'. The release of
fedora to be installed can be controlled through the ``DIB_RELEASE``
variable, which defaults the latest supported release.
