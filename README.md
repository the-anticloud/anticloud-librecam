# LIBRECAM

> Anticloud offline package — upstream: LibreCAM/LibreCAM @ `master`.

## What This Project Does

A CAM plugin for LibreCAD

## Upstream README

LibreCAM
========

A CAM plugin for LibreCAD


Installation
========
Within your LibreCAN directory go to your plugins directory and execute:

git clone https://github.com/LibreCAM/LibreCAM.git

Your plugins directory should look like this:
.
|-- LibreCAM
|-- Makefile
|-- README.plugins
|-- asciifile
|-- plugins.pro
..
..
`-- sample

Edit the file plugins.pro and add LibreCAM to the SUBDIRS section.

Now you can compile LibreCAD and LibreCAM and it will be deployed as such into the resources directory during compilation.

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
