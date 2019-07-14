# abs-lang-npp
A simple Notepad++ user defined language and keyword auto-completion definition files for [ABS](https://www.abs-lang.org/) programming language syntax to be used with default style.

![alt text](https://raw.githubusercontent.com/htejera/abs-lang-npp/master/capture.jpg)

## Overview

This project provides a very simple user defined language file for [Notepad++](https://notepad-plus-plus.org/) that does some basic syntax highlighting for ABS scripts. 

## Usage

### User Defined Language 

Installation instructions (taken from Notepad++ [site](http://docs.notepad-plus-plus.org/index.php?title=User_Defined_Language_Files)):

To add syntax colouring from one of these, the simplest way is o open the User Defined Language panel, click **Import** and navigate to the desired file. If you wish to proceed manually, here is how:

1. Unpack to an **.xml** file, if zipped;
2. If you don't have an **userDefineLang.xml** file already, you can drop this file among your other configuration file, in the Notepad++ Install Folder. It should be named **userDefineLang.xml**. It was reported that "creating the XML file in *C:\Program Files (x86)\Notepad++* on 64-bit Windows 7 didn’t add the syntax highlighting to notepad++. I had to move the XML file to *<user>\AppData\Roaming\Notepad++* for it to work."
3. Otherwise, open both the existing and new file.
* Select all of the new file, copy, and paste at the end of the current file.
* This will have created a spurious *</Notepad_Plus><Notepad_plus>* pair i the middle, each tag on a line by itself. Remove these two consecutive lines.
* Close Notepad++.
  
Your Languages menu will show the newly added language at the bottom, next time you launch Notepad++.

### Auto-completion Definition 

1. On Notepad++ you can find settings by follwing the below: *Settings -> Preferences -> Auto-Completion -> Enable auto-completion on each input.*

2. Rename the [abs-autocomplete.xml](https://github.com/htejera/abs-lang-npp/blob/master/abs-autocomplete.xml) file to **abs.xml**. Copy this file on the **autoCompletion** folder, to be found in the Notepad++ Install Folder, most often *C:\Program Files\Notepad++*

