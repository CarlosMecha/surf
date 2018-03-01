# surf - simple webkit-based browser

surf is a simple Web browser based on WebKit/GTK+.

## Requirements

Ubuntu packages:
 - TODO: Add the webkit packages
 - `dmenu`
 - `libgcr-3-dev`

## Installation

Edit config.mk to match your local setup (surf is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install surf (if
necessary as root):

```bash
$ make clean install
```

## Running surf

```bash
$ surf [URI]
```

See the manpage for further options.

# Credits

Based on `surf` from the guys at Suckless :D
