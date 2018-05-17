This folder contains scripts to build kernel packages:
- amd64_user/: The old one, use fakeroot make-kpkg --initrd. Should work on Fedora.
- debian_build/ or fedora_build/: use "make deb-pkg" provided by kernel developers. Seems newer but not easily to work on Fedora.
