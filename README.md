# KateEditor-JAKT 
`KateEditor-JAKT` is a `syntax` highlighter for the `Kate Editor`, designed specifically for `JAKT language`.

## Install :
To install it, you should copy `Jakt.xml` to the `Kate` syntax folder, depending on your operating system, following the correct path for yourself.

## Unix/Linux
Please add the `Jakt.xml` file to the path provided below:

```Bash
# For all users  
/usr/share/katepart5/syntax

# For current user
$HOME/.local/share/kate/syntax

```
>Note : If the directory `syntax` does not exist, you must create it once in either the path `/usr/share/katepart5/` or `$HOME/.local/share/kate/`.

## Windows 
Please add the `Jakt.xml` file to the path below.

```Bash
%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/syntax
```
>Note : If the directory `syntax` does not exist, you must create one in this path: `%USERPROFILE%/AppData/Local/org.kde.syntax-highlighting/`.

>Note : `%USERPROFILE%/` in Windows is a short path for `C://User/[yourusername]`
