[![WebSight Designs](http://www.websightdesigns.com/img/headerlogo-light.png)](http://www.websightdesigns.com)

sublime-text-snippets
=====================

Sublime Text snippets allow you to create your own shortcuts to writing out snippets of code you reuse frequently. Sublime Text snippets are generally compatible with Textmate snippets. Sublime Text snippet files are XML files with the `.sublime-snippet` file extension.

Full documentation on writing snippets is available from:

http://docs.sublimetext.info/en/latest/extensibility/snippets.html

## Install Instructions

### Mac OS X

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/

    $ git clone https://github.com/websightdesigns/sublime-text-snippets.git

    $ mv sublime-text-snippets/*.sublime-snippet .

### Windows 7 (with Cygwin / Git Bash)

    $ cd "%AppData%\Sublime Text 3\Packages\User"

    $ git clone https://github.com/websightdesigns/sublime-text-snippets.git

    $ mv sublime-text-snippets/*.sublime-snippet .

    $ rm -rf sublime-text-snippets

## Uninstall Instructions

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
    $ mv ./*.sublime-snippet sublime-text-snippets/

## Snippet Categories

* PHP
* JavaScript
* jQuery
* CSS
* HTML
* Global Scope
