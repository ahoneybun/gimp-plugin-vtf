gimp-plugin-vtf
===============

A plugin to open and save vtf files in GIMP.

Developed by [lxndr](https://github.com/lxndr).

## Installation
If you are using ArchLinux, there is a [PKGBUILD](https://gist.github.com/Rahix/a297457945ab236551c9ffbe5f6b9052).
For all other systems use the following instructions:

Clone the git repository into a folder you want to save it to:

```console
git clone https://github.com/linux-source-tools/gimp-plugin-vtf.git
```

Install the required libraries:

- `libgimp2.0-dev`

- `liblcms2-dev`

- `libsquish-dev`

- `libsquish0`

On Debian-based distributions you can install all of these with:

```bash
sudo apt install libgimp2.0-dev liblcms2-dev libsquish-dev libsquish0 libboost1.74-dev  libboost-iostreams-dev     
```

`cd` into the new directory, then make `file-vtf` with:

```console 
make
```

After compiling, move `file-vtf` to `~/.gimp-2.8/plug-ins/`.
