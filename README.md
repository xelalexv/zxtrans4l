# *zxtrans4l*

## TL;DR
*zxtrans4l* is a fork of George Beckett's [*zxtrans*](https://sites.google.com/site/connectedzxspectrum/home-1) project with the aim to make it buildable on Linux out of the box. In addition to removing all Windows-specific artifacts, there currently are only a few minor modifications, that were necessary to make it compile. To see what changed, you can diff against the initial commit.

## Prerequisites
On my system (*Ubuntu 18.04*), I had to install these packages to make it build:

```bash
sudo apt install libspectrum-dev libspectrum8 libserialport-dev libserialport0 z80asm
```

## Building
Just change into the `src` folder and run `make`.
