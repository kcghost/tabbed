# Personal fork of `tabbed`

This is a personal fork of the [tabbed](https://tools.suckless.org/tabbed/) tool from [suckless.org](https://suckless.org/).

It has several changes in the `main` branch:
* [icon](https://tools.suckless.org/tabbed/patches/icon/)
* An updated version of the [xresources patch](https://tools.suckless.org/tabbed/patches/xresources/)
* Changes that support spawning new tabs in the current working directory
* Killing clients by their pid for cleaner shutdown
* Kill tab on right-click as well as middle
* Configurable decorative separator bar
* Don't increase the width of selected tab
* Support draggable tabs
* Personal configuration and keybindings

There are also branches from [upstream](https://github.com/kcghost/tabbed/tree/upstream) containing squashed changes for single feature patches:
* [cwd](https://github.com/kcghost/tabbed/tree/cwd)
* [drag](https://github.com/kcghost/tabbed/tree/drag)
* [separator](https://github.com/kcghost/tabbed/tree/separator)
* [xresources](https://github.com/kcghost/tabbed/tree/xresources)
