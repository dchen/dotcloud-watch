dotcloud-watch
==============

This script watches for changes in the current directory and does a push to
DotCloud for the named app upon any change. It's a quick script that hasn't
really been tested. It really only works if you don't use a version control
system in its current implementation.

Setup
-----

Drop the dotcloud-watch script somewhere in your PATH, like /usr/local/bin,
and make sure it is executable.

Usage
-----

Change to the directory where your dotcloud.yml file is and run dotcloud-watch
with your app name as its only argument:

    cd myapp
    dotcloud-watch myapptest

License/Credit
--------------

This is a prototype of a concept by Gabriel Grant. Maintained by David E.
Chen.
