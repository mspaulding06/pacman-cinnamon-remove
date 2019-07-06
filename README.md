# Pacman Cinnamon Remove Application

This is a script that can be installed on an Arch or Manjaro system using Pacman.

It will allow the use of the "Uninstall" command from the cinnamon menu.

## Prerequisites

* python2
* pygtk
* pamac-gtk

## Installation

```bash
$ sudo cp cinnamon-remove-application /usr/bin/
```

NOTE: The cinnamon menu applet looks for an executable with the filename `/usr/bin/cinnamon-remove-application` and
if it finds one then you will now see the "Uninstall" option when you right-click on items in the menu.

