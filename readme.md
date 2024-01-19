# Virtiso - Minified Virtio ISO #

This repository contains a minified image of the KVM/QEMU Virtio drivers for Windows guests.

It minimizes the standard ISO of 600 MB to just 40 MB in size.

# Methods used

  - Stripped ARM64/i386/x86 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools
  - Removed support for Windows XP
  - Removed support for Windows Server 2003
  - Removed support for Windows Server 2008
  - Removed support for Windows Server 2012
