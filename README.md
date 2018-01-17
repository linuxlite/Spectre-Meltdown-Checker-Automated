Spectre Meltdown Checker Automated
==============================

An Automated Spectre Meltdown downloader and checker.
Should work on most Linux Distros.

## What it does

Downloads the latest version of **spectre-meltdown-checker.sh** from [https://github.com/speed47/spectre-meltdown-checker](https://github.com/speed47/spectre-meltdown-checker) and runs the script. 

## Dependencies:

<pre>
wget
xterm
</pre>

## Requirements:
<pre>
superuser (sudo, su)
</pre>

## License ![License](https://img.shields.io/badge/license-GPLv2-green.svg)

This project is under the GPLv2 license. Unless otherwise stated in individual files.

## Author
- [Jerry Bezencon](https://github.com/linuxlite/)

Instructions
================

Download as zip or clone this repository.
Extract zip or cd to cloned repository (spectre-meltdown-checker)

<pre>
chmod +x sm-*
</pre>

<pre>
if
</pre>

you are using XFCE with Thunar:

<pre>
xfconf-query --channel thunar --property /misc-exec-shell-scripts-by-default --create --type bool --set true
</pre>

and double click on sm-start.

<pre>
else
</pre>

<pre>
./sm-start
</pre>

![](https://i.imgur.com/Cl4KQhW.png)

![](https://imgur.com/CSQErHb.png)

![](https://imgur.com/HRWRsuK.png)
