<h1 align="center">VirtISO<br />
<div align="center">
<a href="https://github.com/qemus/virtiso"><img src="https://github.com/qemus/virtiso/raw/master/.github/logo.png" title="Logo" style="max-width:100%;" width="128" /></a>
</div>
<div align="center">
  
  [![Build](https://github.com/qemus/virtiso/actions/workflows/build.yml/badge.svg)](https://github.com/qemus/virtiso/)
  [![Version](https://img.shields.io/github/v/release/qemus/virtiso?label=version&sort=semver&display_name=release&color=066da5)](https://github.com/qemus/virtiso/releases)
  [![Size](https://img.shields.io/badge/size-26.8_MB-steelblue?style=flat&color=066da5)](https://github.com/qemus/virtiso/releases)
  
</div></h1>

VirtISO is a slim image of the VirtIO drivers for Windows guests.

It minimizes the [official ISO](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/latest-virtio/) from 700 MB to just 25 MB in size.

# Features ✨

  - Stripped all x86/i386/ARM drivers
  - Stripped all .PDB (debug symbol) files
  - Stripped Guest Agent and Guest Tools

# Download

  You can download the [latest version](https://github.com/qemus/virtiso/releases/download/v0.1.271-1/virtio-win-0.1.271.iso) from the [Releases](https://github.com/qemus/virtiso/releases) page.

# Usage 🚀
  
  It contains every x64 driver the official image has, and even the .MSI installer, so there is zero loss of functionality.

> [!TIP]
> See also [VirtISO WHQL](https://github.com/qemus/virtiso-whql/) if you need signed drivers, [VirtISO x86](https://github.com/qemus/virtiso-x86/) for x86 drivers and [VirtISO ARM](https://github.com/qemus/virtiso-arm/) for ARM64 drivers.

# Stars 🌟
[![Stars](https://starchart.cc/qemus/virtiso.svg?variant=adaptive)](https://starchart.cc/qemus/virtiso)

# Disclaimer ⚖️

  *This project contains binaries provided by Red Hat, Inc. and/or its affiliates.*
