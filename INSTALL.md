# Installation

Instructions on how to build and install cscope used for [buttercup](https://github.com/trailofbits/buttercup).

## Download

```bash
git clone https://github.com/trail-of-forks/buttercup-cscope
cd buttercup-cscope/
```

## Build

```bash
autoreconf -i -s
./configure && make
./src/cscope --version
```

## Install

```bash
sudo make install
```

## Development

```bash
make clean && ./configure && make
```

## Uninstall

```bash
sudo make uninstall
```
