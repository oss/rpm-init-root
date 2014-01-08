rpm-init-root
=============
Set up a new user for building RPMs.

Usage
-----
This script initializes an RPM build tree for a normal user based off of the
usual RPM macros. To use this, you should be in your home directory before
running the script.

Then, simply doing

    $ rpm-init-root

should create the required folders for you to begin making RPMs.o

Note that this script should only be run on a build machine.

Requires
--------
- rpm
