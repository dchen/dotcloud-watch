dotcloud-watch
==============
This script watches for changes in the current directory and does a push to
DotCloud for the named app upon any change. It's a quick script that hasn't
really been tested.

Setup
-----
Drop the dotcloud-watch script somewhere in your PATH, like /usr/local/bin,
and make sure it is executable.

Usage
-----
Change to the directory where your dotcloud.yml file is and run dotcloud-watch
with your app name as its only argument:

    cd myapp
    dotcloud-watch myapp
