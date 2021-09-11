# dmenukeepass

This is a dmenu wrapper for retriving passwords from keepass files written in python3.

For this script to work, you need to have dmenu and a notify daemon like dunst.

For Arch users : `pacman -S dmenu dunst`

## Installation

Install python requirements.

Run dmenukeepass_daemon after the running of the x11 server while pasting

`/path/to/dmenukeepass_daemon /path/to/database.kdbx &`

in your .profile after startx for example.

Bind keepass_close and keepass_open scripts to shortcuts or put them in in /usr/bin.
