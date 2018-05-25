# WEOML Syntax
WEO keys + HTML = COLORS! HTML syntax supercharged to recognize WEO keys in Sublime Text 3.
This package provides additional syntax highlighting to proprietary WEO Media "Keys" in addition to basic HTML syntax highlighting. It is derived from Sublime's standard HTML highlighting. 

## Other Bits
Also included...
  - Auto completions of all the WEO keys with corresponding parameters
  - Keyboard shortcuts for manipulating WEO brackets
  - Snippets for commonly used code

## Other Packages To Install
  - sublime tutor
  - ghost text
  - bracket highlighter
  - css format
  - default file type

### Optional
  - color highlighter
  - emmet
  - html-css-js-prettify
  - RegReplace

## Auto Completions
1. Open the Sublime Text personal settings file:
    - Mac OS X: Sublime Text > Preferences > Settings - User
    - Windows: Preferences > Settings - User
    - Linux: Preferences > Settings - User

2. Add 	"auto_complete_selector": "source, text", at the top, within the square brackets. 

## Default File Set Up
1. Open a new file in sublime.
2. paste the following:
    {
      "default_new_file_syntax": "WEOML.sublime-syntax",
      "default_new_window_syntax": "WEOML.sublime-syntax",
      "use_current_file_syntax": false
    }
3. Save as "default_file_type.sublime-settings" into the following location
  - /Packages/User/default_file_type.sublime-settings
    - to find the user packages folder
     - Mac OS X: Sublime Text > Preferences > Browse Packages
     - Windows: Preferences > Browse Packages
