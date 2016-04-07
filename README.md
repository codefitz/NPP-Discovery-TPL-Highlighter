##Notepad++ TPL Syntax Highlighting

### Description

A TPL syntax highlighter and auto-completion with parameters hints for BMC's Atrium Discovery and Dependency Mapping (ADDM) with partial blocking functionality.

This is a fork from https://github.com/codefitz/.

Added support for  TPL version 1.8

### Installation

This is an improvement on the original syntax file from BMC Discovery Community, download the installation files from [here](https://communities.bmc.com/communities/docs/DOC-20540/version/1):

1. Copy the tpl.xml file into <Notepad++_install_directory>\plugins\APIs
<<<<<<< HEAD
1. Go to c:\Documents and Settings\<your_username>\Application Data\Notepad++ OR C:\Users\<your_username>\AppData\Roaming\Notepad++
1. If there is an existing userDefineLang.xml present, take a backup, or merge the xml with existing custom UDL syntax.
1. Copy the new userDefineLang.xml to that location
1. Close Notepad++ and restart
1. TPL should be available in the language list, and files saved as .tpl should use it automatically

### Update

Added a new syntax file for queries stored in text files (uses extension *.twq).
=======
2. Go to c:\Documents and Settings\<your_username>\Application Data\Notepad++ OR C:\Users\<your_username>\AppData\Roaming\Notepad++
3. If there is an existing userDefineLang.xml present, take a backup, or merge the xml with existing custom UDL syntax.
4. Copy the new userDefineLang.xml to that location
5. Close Notepad++ and restart
6. TPL should be available in the language list, and files saved as .tpl should use it automatically
7. To enable Autocomplete and parameters hint, go to Settings -> Preferences.. -> Backup/Auto-Completion -> Enable auto-completion on each input | Function parameters hint on input
>>>>>>> refs/remotes/origin/pr/1
