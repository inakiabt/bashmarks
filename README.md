### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

## Install

1. git clone git://github.com/inakiabt/bashmarks.git
2. make install
3. source **~/.local/bin/bashmarks.sh** from within your **~.bash\_profile** or **~/.bashrc** file

## Shell Commands

    ms <bookmark_name> - Saves the current directory as "bookmark_name"
    mg <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    mp <bookmark_name> - Prints the directory associated with "bookmark_name"
    md <bookmark_name> - Deletes the bookmark
    ml                 - Lists all available bookmarks

## Example Usage

    $ cd /var/www/
    $ ms webfolder
    $ cd /usr/local/lib/
    $ ms locallib
    $ ml
    $ mg web<tab>
    $ mg webfolder

## Where Bashmarks are stored

All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.
