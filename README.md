asdf
====

Initializes [asdf], installing it using git if not installed yet. 
Unlike the original [zimfw/asdf] this version does not bypass the shims if [direnv plugin] is detected.

Settings
--------

The path of `ASDF_DIR`, where asdf is installed, is checked among the usual
directories created by Homebrew or Pacman, or the default `${HOME}/.asdf`. You
can define `ASDF_DIR`, before where this module is initialized, to customize
it's path:

    ASDF_DIR=/path/to/asdf_dir

[asdf]: https://github.com/asdf-vm/asdf
[direnv plugin]: https://github.com/asdf-community/asdf-direnv
[zimfw/asdf]: https://github.com/zimfw/asdf
