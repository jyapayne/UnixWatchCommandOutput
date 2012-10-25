UnixWatchCommandOutput
======================

Allows the user to input a program and watch the output. 

This is pretty much the same as watch except that it allows scrolling output.

usage:
pwatch command [command args]

examples:

pwatch tree -v

pwatch grep "stuff" *

To exit, ctrl-c or ESC.

Right now, this program will refresh every 1 second, and it is not configurable.
I might update this in the future to be configurable.


Requirements:

python 2.7.2