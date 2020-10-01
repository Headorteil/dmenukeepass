# dmenukeepass

This is a dmenu wrapper for keepassxc-cli written in python3.

For this script to work, you need to have dmenu, keepassxc and a notify daemon like dunst.

For Arch users : `pacman -S dmenu keepassxc dunst`

## Installation

Install python requirements.

Put Dmenukeepass.service in /etc/systemd/system, replace the path, the user and the group.

Bind keepass_close and keepass_open scripts to shortcuts or put them in in /usr/bin.

Then, you just need to change the path of the keepass.kdbx in dmenukeepass_daemon and it should work.
