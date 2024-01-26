<h1 align="center">Virtiso<br />
<div align="center">
<img src="https://github.com/qemus/virtiso/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" />
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso/)
  [![Version](https://img.shields.io/github/v/tag/qemus/virtiso?label=version&sort=semver&color=066da5)](https://github.com/qemus/virtiso/releases)
  [![Size](https://img.shields.io/badge/size-25.9_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso/releases)
  
</div></h1>

Virtiso is a slim image of the KVM/QEMU Virtio drivers for Windows guests.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) of 600 MB to 25 MB in size.

# Methods used

  - Stripped ARM64/i386/x86 drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Usage

  This can be used for all AMD64 installations of Windows XP and up, and Windows Server 2003 and up.
  
  It contains every AMD64 driver the official image has, and even the .MSI installer, so there is zero loss of functionality.

# Disclaimer

  This project contains binaries provided by Red Hat, Inc. and/or its affiliates.
