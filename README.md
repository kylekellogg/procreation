# Procreation

A helpful utility that will assist you in creating Löve2D executables for Windows (32-bit and 64-bit) and Mac OSX.

## Installation

```sh
curl -fsSL https://raw.github.com/sqow/procreation/master/procreation -o /usr/local/bin/procreation; chmod a+x /usr/local/bin/procreation;
```

## Usage

```sh

Usage: $0 [-bhtn] input target

It is assumed that input will be a directory that already exists. If it doesn't, this will fail.
Target may be a directory that does not yet exist. If it doesn't, it will be created. Otherwise, it will be cleaned before use.

Options:
  -b      Bust cache: Force download of executables again.
  -h      Help; this message.
  -t      Title of the game, for the executables.
  -n      Name for Mac Bundle Identifier, e.g. com.whatever.gamename

```
