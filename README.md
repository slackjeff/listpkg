Listpkg (Lists packages are (installed or not) in Slackware.)
VERSION: 0.1a
but what is listpkg anyway?
Listpkg is a utility for the Slackware system
which lists whether one or more packages are installed on the system
written in sh 'bourne shell' script.

Simple Usage:
listpkg [package1] [package2]*
example:
$ listpkg kdenlive
$ listpkg audacity kdenlive guvcview



Install:
Need root for installation!
$ su

Copy and paste in your terminal.
# cd /usr/bin && wget -q --show-progress "https://notabug.org/jeffersonrocha/ListPkg/raw/master/listpkg" && chmod +x listpkg
