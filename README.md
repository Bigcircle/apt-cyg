apt-cyg - fork from official project [apt-cyg](https://code.google.com/p/apt-cyg/)

=======

apt-cyg is a command-line installer for Cygwin which cooperates with Cygwin Setup and uses the same repository. The syntax is similar to apt-get. Usage examples:

* "apt-cyg install <package names>" to install packages
* "apt-cyg remove <package names>" to remove packages
* "apt-cyg update" to update setup.ini
* "apt-cyg show" to show installed packages
* "apt-cyg find <pattern(s)>" to find packages matching patterns
* "apt-cyg describe <pattern(s)>" to describe packages matching patterns
* "apt-cyg packageof <commands or files>" to locate parent packages

Quick start
-----------

apt-cyg is a simple script. Once you have a copy, make it executable:

  # cp apt-cyg /usr/bin/apt-cyg && chmod +x /usr/bin/apt-cyg

Optionally place apt-cyg in a bin/ folder on your path.

For easy use, alias it. And then use apt-cyg, for example:

  # alias aa="apt-cyg"

  # aa install nano

Contributing
------------

This project has been re-published on GitHub to make contributing easier. Feel free to fork and modify this script.

The [Google Code project](https://code.google.com/p/apt-cyg/) has a list of open issues.
