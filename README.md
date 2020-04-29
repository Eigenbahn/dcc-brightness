# dcc-brightness

Control the brightness of your screen in CLI, or define shortcuts.

Script `dcc-brightness` is a convenient wrapper around `ddcutil` ([doc](https://www.ddcutil.com/), [source](https://github.com/rockowitz/ddcutil)).

As the later can be quite slow, we rely on a cache file to speed things up: `/tmp/dcc.cache`.


## Installation

Install `ddcutil`.

Put file `dcc-brightness` somewhere in your path (e.g. `/usr/local/bin`, `~/.local/bin` or `~/bin`) and make it executable.


## Usage

Lower the brightness value by 10:

    dcc-brightness --delta -10

Increase the brightness value by 10:

    dcc-brightness --delta 10

Set the brightness value to 50:

    dcc-brightness --set 10
