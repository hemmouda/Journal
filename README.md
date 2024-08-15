# Journal &nbsp; ![DEVELOPMENT STATUS: completed](https://badgen.net/badge/DEVELOPMENT%20STATUS/completed/green)
A bash script for your simple journaling.

Write your daily journals and read them with ease, or keep them safe with a password.

## Basic usage:
Simply run `journal` with no arguments to write a new journal for today, or add a new entry.

Some settings can be modified inside the script, like wether or not to lock the journals by default, what editor to use, and some other stuff.

To read a journal, simply specify the date it was written on. Like so for example:
```console
$ journal 1970 01 01
```

For all the possibilities, run:
```console
$ journal h
```

## How-to:
1. Put the [**journal**](journal) script with your other **bin**aries, or in a separate folder, but then don't forget to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
2. Add execution rights to it: ```$ chmod u+x journal```
3. Rehash to use instantly: ```$ rehash```

## Note:
Some commands may not work with Linux distros. Only tested on MacOS.

## ⚠️ &nbsp; Important note:
Keep in mind that if you lose the password for a journal, that journal is locked forever and cannot be unlocked.
