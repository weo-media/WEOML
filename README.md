# WEOML Syntax
It's WEO keys + HTML = COLORS! We've taken HTML syntax and supercharged it to recognize WEO keys in Sublime Text 3.
This package provides syntax highlighting to proprietary WEO Media "Keys" in addition to basic HTML syntax highlighting. It is derived from Sublime's standard HTML highlighting. 

## Other Bits
Also included...
  - Auto completions of all the WEO keys with corresponding parameters
  - Keyboard shortcuts for manipulating WEO brackets
  - Snippets for commonly used code

## Other Packages To Install
  - sublime tutor
  - ghost text
  - bracket highlighter
  - default file type
  - color highlighter

### Optional
  - emmet
  - html-css-js-prettify
  - css format
  - text pastry

## Auto Completions
1. Open the Sublime Text personal settings file:
    - Mac OS X: Sublime Text > Preferences > Settings - User
    - Windows: Preferences > Settings - User

2. Add the following code on a new line after the first curly brace (`{`)	:<br><br>
`
  "auto_complete": true,<br>
	"auto_complete_commit_on_tab": true,<br>
	"auto_complete_cycle": true,<br>
	"auto_complete_selector": "source, text",<br>
	"auto_complete_with_fields": true,<br>
	"tab_size": 2,<br>
	"translate_tabs_to_spaces": true,
`

## Default File Set Up
1. Open a new file in sublime.
2. paste the following:<br><br>
`
  {<br>
  "default_new_file_syntax": "WEOML.sublime-syntax",<br>
  "default_new_window_syntax": "WEOML.sublime-syntax",<br>
  "use_current_file_syntax": false<br>
  }
`
      
3. Save as "default_file_type.sublime-settings" into the following location
  - /Packages/User/default_file_type.sublime-settings
    - to find the user packages folder
      - Mac OS X: Sublime Text > Preferences > Browse Packages
      - Windows: Preferences > Browse Packages
