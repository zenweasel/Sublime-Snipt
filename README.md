## Description
Sublime Snipt is a Sublime Text 2 plugin that will sync with snipt.net. Once activated it will download all of your snipts from snipt.net and turn each of them into a sublime snippet.

_This version is a copy of **forgot name_put here** which was a fork of the one available through Package Control.
I made a couple of small fixes and it worked for me. I hope to merge changes of any value back into the original Package._



### Using Git
Go to your Sublime Text 2 Packages directory and clone the repository using the command below:

    git clone https://github.com/zenweasel/Sublime-Snipt

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `snipt`
* Copy the folder to your Sublime Text 2 `Packages` directory

## Usage
### Sync first
Once installed you should be able to access the sync command in two ways.

+ Right click and select Snipt Tools followed by "Sync with snipt.net"
+ Main Menu: Edit ~> Snipt Tools ~> "Sync with snipt.net"

### Sublime Snippets
All snipt.net snippets can be called up as you type "snipt" in the Sublime editor.

## To-do's
+ User option to limit snipts via tags (only display css snippets on css files)
+ Select and Highlight text to send to snipt.net
+ Python: thread snipt downloading


Sublime-Snipt for Brent
=============

A Version of the Sublime-Snipt Package that works for me

## My To-do's
+ Add error handling when encountering files with non-unicode characters
+ Parse shebang lines to try and set scope
