# Hex computer

To make the process of understanding how the Hex computer simulators and
compilers work I've written some build scripts to make the file names more
readable. There are also scripts with functions that will run programs on the
simulators, they are to ease development of programs and help users understand
how the simulators work.

## Dependencies
[SCons](www.scons.org)
    
Debian/Ubuntu (and derivatives):

    $ sudo apt-get install scons

Arch Linux:

    $ sudo pacman -S scons

Mac OS X:

    $ sudo brew install scons

## How to build

Run the command:

    scons

then have a look in the `build` folder produced.
