

https://github.com/c4pt000/FFmpeg


![s1](https://raw.githubusercontent.com/c4pt000/caja/master/image-details-screenshot-machine-info-Tcamera-type-Tmodel.png)


FFmpeg README
=============

# MISSING HERE

* https://raw.githubusercontent.com/c4pt000/FFmpeg/master/preserve-metadata-ffmpeg-from-conversion.png
![s1](https://raw.githubusercontent.com/c4pt000/FFmpeg/master/preserve-metadata-ffmpeg-from-conversion.png)




# SHOULD BE HERE WITH -i import conversion from EXIF DATA or file remote location metadata tag

https://raw.githubusercontent.com/c4pt000/FFmpeg/master/image-details-screenshot-machine-info-Tcamera-type-Tmodel.png
![s1](https://raw.githubusercontent.com/c4pt000/FFmpeg/master/image-details-screenshot-machine-info-Tcamera-type-Tmodel.png)

https://raw.githubusercontent.com/c4pt000/FFmpeg/master/taken-with-camera-details-metadata-png.png
![s1](https://raw.githubusercontent.com/c4pt000/FFmpeg/master/taken-with-camera-details-metadata-png.png)




[![Build Status](https://travis-ci.org/mate-desktop/caja.svg?branch=master)](https://travis-ci.org/mate-desktop/caja)
[![Release](https://img.shields.io/github/v/release/mate-desktop/caja)](https://github.com/mate-desktop/caja/releases)
[![IRC Network](https://img.shields.io/badge/irc-freenode-blue.svg "IRC Freenode")](https://webchat.freenode.net/?channels=mate)

<h1 align="center">
  <img src="https://github.com/mate-desktop/mate-icon-theme/raw/master/mate/256x256/apps/system-file-manager.png"  alt="Caja" width="128" height="128">
  <br />
  Caja
</h1>

<p align="center"><b>The file manager for the MATE desktop</b></p>
<div align="center"><img src="https://mate-desktop.org/gallery/1.24/english/007.png" alt="Caja Screenshot"></div>

## Installation

### Ubuntu

```bash
sudo apt install caja
```

### Fedora

```bash
sudo dnf install caja
```

## Building

### Source

You'll need the following dependencies:

  * `exempi`
  * `gobject-introspection`
  * `libnotify`
  * `libexif`
  * `gvfs`
  * `mate-common`
  * `mate-desktop`

### Building

```bash
git clone --recurse-submodules https://github.com/mate-desktop/caja.git
cd caja
./autogen.sh --prefix=/usr
make
make install
```

## Hacking on Caja

Please see the HACKING file for information about hacking on caja.

## How to report bugs / errors in translations

Bugs should be reported in GitHub

https://github.com/mate-desktop/caja/issues

We are using transifex for translations. https://www.transifex.com/mate/MATE/dashboard/

Please create an account, become a member of your language team and fix it there.

## Package status

[![Packaging status](https://repology.org/badge/vertical-allrepos/caja.svg)](https://repology.org/project/caja/versions)
