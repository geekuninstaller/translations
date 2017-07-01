You will need a text editor that supports editing UTF-8 formatted XML files (you can try free [Notepad++](https://notepad-plus-plus.org/) or [Brackets](http://brackets.io/)).

# Translating the app

Always leave %s or %d in the string, it's a replacement pattern required by the program. For example, the string "%s uninstalled" will be expanded to "Firefox uninstalled" when Firefox is uninstalled. Be careful when escaping HTML characters.

Do not edit LangID of an existent language file. This is done by us using [Microsoft languages table](http://msdn.microsoft.com/en-us/goglobal/bb964664.aspx).

# Translating the website

Create a new .yml file (named using [ISO 639-1](https://en.wikipedia.org/wiki/ISO_639-1)) based on en.yml.
