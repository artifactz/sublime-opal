sublime-opal
============

Syntax definition of the Opal programming language for syntax highlighting in Sublime Text 2.

#### How to use
```
cd ~/.config/sublime-text-2/Packages/
git clone https://github.com/artifactz/sublime-opal.git Opal
```
Then in Sublime Text you can [Ctrl]+[Shift]+P
```
Set Syntax: Opal
```
whenever you want. Opal files (*.impl, *.sign) are being recognized.

#### Sublime Package Control
You can make your life easier using [Sublime Package Control](https://sublime.wbond.net/installation) and get updates automatically.  
If you've got it installed:  
[Ctrl]+[Shift]+P
```
Package Control: Add Repository
```
and use this site's address: `https://github.com/artifactz/sublime-opal`  
Then [Ctrl]+[Shift]+P
```
Package Control: Install Package
sublime-opal
```
_Please note that the manual setup and installation through Package Control are_ **XOR**_ed. Doing both results in two distinct installations of OPAL syntax highlighting, which probably is not what you want._  
_If you're using a manually installed OPAL highlighting and want to try out adding it through Package Control, please delete_ `~/.config/sublime-text-2/Packages/Opal` _first._
