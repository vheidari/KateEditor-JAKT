# KateEditor-JAKT 
KateEditor-JAKT, is a JAKT language syntax highlighter for Kate Editor

## Install :
To install it, you should copy `Jakt.xml` to `Kate` syntax folder. depend on your operation system flow right path for your self.

## Unix/Linux
Please add the `Jakt.xml` file to the path provided below:

```Bash
# For all users  
/usr/share/katepart5/syntax

# For current user
$HOME/.local/share/kate/syntax

```
>Note : If directory `syntax` isn't exist, you msut create once in this path `/usr/share/katepart5/` or `$HOME/.local/share/kate/`.

## Windows 
Please add `Jakt.xml` file to the path below :

```Bash
%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/syntax
```
>Note : if directory `syntax` isn't exist, you must create one in this path : `%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/`

>Note : `%USERPROFILE%/` in Windows is a short path for `C://User/[yourusername]`
