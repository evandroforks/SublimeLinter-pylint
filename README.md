SublimeLinter-pylint
=========================

[![Build Status](https://travis-ci.org/SublimeLinter/SublimeLinter-pylint.svg?branch=master)](https://travis-ci.org/SublimeLinter/SublimeLinter-pylint)

This linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to [pylint](http://www.pylint.org/).
It will be used with files that have the "python" syntax.


## Installation

SublimeLinter must be installed in order to use this plugin.

Before using this plugin, ensure that `pylint` (1.0 or later) is installed on your system.
To install `pylint`, do the following:

1. Install [Python](http://python.org) and [pip](http://www.pip-installer.org/en/latest/installing.html). If you plan to code in Python 3, you will need to install `pip` for Python 3 as well.

1. Install `pylint` by typing the following in a terminal, replacing ‘x’ with the minor version installed on your system:
   ```bash
   # For python 2.x
   [sudo] pip-2.x install pylint

   # For python 3.x
   [sudo] pip-3.x install pylint

   # On Windows, for python 2.x
   c:\Python2x\Scripts\pip.exe install pylint

   # On Windows, for python 3.x
   c:\Python3x\Scripts\pip.exe install pylint
   ```

Please make sure that the path to `pylint` is available to SublimeLinter.
The docs cover [troubleshooting PATH configuration](http://sublimelinter.com/en/latest/troubleshooting.html#finding-a-linter-executable).

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `SublimeLinter-pylint` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## Settings

- SublimeLinter settings: http://sublimelinter.com/en/latest/settings.html
- Linter settings: http://sublimelinter.com/en/latest/linter_settings.html

Pylint can be configured using `.pylintrc` configuration files and inline comments, more information in [the pylint docs](https://pylint.readthedocs.io/en/latest/faq.html#message-control).
