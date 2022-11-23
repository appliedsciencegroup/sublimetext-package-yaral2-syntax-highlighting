# YARA-L2 package for Sublime Text

<img src=images/yara_syntax_example.gif>

## Synopsis

This is a [YARA-L2](https://cloud.google.com/chronicle/docs/detection/yara-l-2-0-overview) plugin for
[Sublime Text](http://www.sublimetext.com).
This package contains syntax highlighting.

## Installation

With [Package Control](https://packagecontrol.io):

1. Run Package Control: `Install Package` command
2. Find `YaraL2Syntax` plugin.
3. Install it.
4. Restart Sublime Text if required.

Manually:

1. Go to your packages folder. (In ST menu, `Browse Packages`)
2. Clone or [download](https://github.com/yalefox/languagepack-yaraL2/archive/refs/heads/main.zip)
git repo into the folder
3. Restart Sublime Text if required.

## Customize color scheme

#### Solution 1 - Using Yaral color scheme default with base Mariana color scheme
1. Select Yaral.sublime-color-scheme (In ST menu, `Preferences` -> `Select Color Scheme ...` -> `Yaral`) 

#### Solution 2 - Using Yaral color schema with your own color schema
1. Select Yaral.sublime-color-scheme (In ST menu, `Preferences` -> `Customize Color Scheme ...` -> Paste all the content of File `Customize-color.yaml` overwrite to customize windown and `Save`) 

## Debug and refine color schema

1. Find the scope and context will asssign this color stype
In yaral file you want to audit, press `Ctrl + Alt + Shift + P (Window)` or `Ctrl + Shift + P (Mac)`, 
You can see scope and context for this highlighting the language,
In the context order, you can find how to highlight this word.
2. Customize your color of scope define for this word
In your color schema (`Custom` or `Yaral`), find the `scope` is the prefix of `scope in debuging context` in `rule` tag, change your color style if needed.
3. And you also can change your `scope` in sublime-syntax if you want and style it as you want.

## Snippets

* rule
* meta
* events
* match
* outcome
* condition
* strings

## Contributors

You could contribute by opening an issue or create a pull request.

## License

This plugin is under [GPLv3](LICENSE.txt)
