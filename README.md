##Notepad++ TPL Syntax Highlighting

### Description

A TPL syntax highlighter for BMC's Atrium Discovery and Dependency Mapping (ADDM) with partial blocking functionality.

This is a fork from [cwill747's](https://github.com/cwill747) improvement, with alternative colour scheme and a fix to comment lines where syntax would not highlight without whitespace character between `//` and the comment. Some of the keywords have also been re-assigned.

Autocomplete is available through *Settings -> Preferences.. -> Backup/Auto-Completion -> Enable auto-completion to each input (checkbox)*

### Installation

This is an improvement on the original syntax file from BMC Discovery Community, download the installation files from [here](https://communities.bmc.com/communities/docs/DOC-20540/version/1):

1. Copy the tpl.xml file into <Notepad++_install_directory>\plugins\APIs
1. Go to c:\Documents and Settings\<your_username>\Application Data\Notepad++ OR C:\Users\<your_username>\AppData\Roaming\Notepad++
1. If there is an existing userDefineLang.xml present, take a backup, or merge the xml with existing custom UDL syntax.
1. Copy the new userDefineLang.xml to that location
1. Close Notepad++ and restart
1. TPL should be available in the language list, and files saved as .tpl should use it automatically
