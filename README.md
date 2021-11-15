# python-interactive-rename

# description

This tool is the answer to "How to rename a file interactively in Linux / command line ?"

interactive file renamer with prefilled named.

handy in shells Unixes, Mac even WSl for windows


# usage

[![demo](https://asciinema.org/a/9WdYV6EdSOxORDN8U3oqDeX4H.svg)](https://asciinema.org/a/9WdYV6EdSOxORDN8U3oqDeX4H)


	$ ren README.md
	new name: READ sdfiusdf yeah ME.md
	rename to:[READ sdfiusdf yeah ME.md]
	rename ? y/n[Y]: 

file is renamed

	$ ls -rt | head -1 
	READ sdfiusdf yeah ME.md


# note on readline on a mac
note it uses readline, there may be issues on a mac
https://stackoverflow.com/questions/327251/why-is-the-python-readline-module-not-available-on-os-x
https://superuser.com/questions/1404715/readline-for-python-3-6-on-mac-10-14

I guess installing gnureadline with brew should fix the problem if any (not tested)

	brew install gnureadline

