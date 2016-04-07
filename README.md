##Notepad++ TPL Syntax Highlighting - TPL version 1.8

### Description

A TPL syntax and query language highlighter, auto-completion with parameters hints for BMC's Discovery (previously ADDM) tool with partial blocking functionality.

### Installation

This is an improvement on the original syntax file from BMC Discovery Community, (Orginal [here](https://communities.bmc.com/communities/docs/DOC-20540/version/1)):

1. Copy the tpl.xml and twq.xml files into <Notepad++_install_directory>\plugins\APIs
2. Go to c:\Documents and Settings\<your_username>\Application Data\Notepad++ OR C:\Users\<your_username>\AppData\Roaming\Notepad++
3. If there is an existing userDefineLang.xml present, take a backup, or merge the xml with existing custom UDL syntax.
4. Copy the new userDefineLang.xml to that location
5. Close Notepad++ and restart
6. TPL should be available in the language list, and files saved as .tpl should use it automatically

To enable Autocomplete and parameters hint, go to Settings -> Preferences.. -> Backup/Auto-Completion -> Enable auto-completion on each input | Function parameters hint on input
