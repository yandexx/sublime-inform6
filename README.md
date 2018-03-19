# sublime-inform6
Inform 6 syntax highlighting for Sublime Text 2/3

**Inform 6** is a language for creating text adventures (interactive fiction): http://inform-fiction.org/

This package is based on the original syntax definition made by Chris Thomas.

Syntax highlighting is automatically selected for **.inf** files. For **.h** files you have to select it manually (due to a conflict with C/C++ definitions).

## Installation via Package Control (recommended)

1. If you don’t have Package Control installed yet, do so via **Tools > Install Package Control…** on ST3 or via [instructions](https://packagecontrol.io/installation) for ST2.
2. Hit Ctrl+Shift+P (Cmd+Shift+P), type **install** and select **Package Control: Install Package**.
3. Type **inform** and then select **Inform 6**.
4. Done!

## Manual installation

Download and copy the **inform6.tmLanguage** file to the Sublime Text user packages folder:

* Windows: `%APPDATA%\Sublime Text 3\Packages`
* OS X: `~/Library/Application Support/Sublime Text 3/Packages`
* Linux: `~/.config/sublime-text-3/Packages`

## Building

Use the **PackageDev** package to convert **inform6.YAML-tmLanguage** to **inform6.tmLanguage**.
