<h1 align="center">Virtiso<br />
<div align="center">
<img src="https://github.com/qemus/virtiso/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" />
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso/)
  [![Version](https://img.shields.io/github/v/tag/qemus/virtiso?label=version&sort=semver&color=066da5)](https://github.com/qemus/virtiso/releases)
  [![Size](https://img.shields.io/badge/size-40.2_MB-steeelblue?style=flat&color=066da5&label=size)](https://github.com/qemus/virtiso/releases)
  
</div></h1>

This repository contains a minimal image of the KVM/QEMU Virtio drivers for Windows guests.

It minimizes the standard ISO of 600 MB to just 40 MB in size.

# Methods used

  - Stripped ARM64/i386/x86 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools
  - Removed support for Windows XP
  - Removed support for Windows Server 2003
  - Removed support for Windows Server 2008
  - Removed support for Windows Server 2012
