******************Welcome to******************
`\  \    / _/__/ __ \  |  \/  |___  | |_| __  The`
` \  \/\/ |  __||  | | |      / _ \_| | ||_ \ Best`
`  \      |  __||__| | | |\/| | __/ _ | / _ | Dental`
`   \_/\_/|____|____/  |_|  |_\___\__.|_\__.| Marketing`

You've just installed the... 
# WEOML Syntax
It's WEO keys + HTML = COLORS! We've taken HTML syntax and supercharged it to recognize WEO keys in Sublime Text 3.
This package provides syntax highlighting to proprietary WEO Media "Keys" in addition to basic HTML syntax highlighting. It is derived from Sublime's standard HTML highlighting. 

## Other Bits
Also included...
  - Auto completions of all the WEO keys with corresponding parameters
  - Snippets for commonly used code
  - DearDoctor Video IDs
  - completions for bootstrap-tp classes

## Other Packages To Install
  - sublime tutor
  - ghost text
  - bracket highlighter
  - default file type
  - color highlighter
  - text pastry

### Optional
  - emmet
  - html-css-js-prettify
  - css format

## Auto Completions
1. Open the Sublime Text personal settings file:
    - Mac OS X: Sublime Text > Preferences > Settings
    - Windows: Preferences > Settings

2. Add the following code on a new line after the first curly brace (`{`)   


    "auto_complete": true,
    "auto_complete_commit_on_tab": true,
    "auto_complete_cycle": true,
    "auto_complete_selector": "source, text",
    "auto_complete_with_fields": true,
    "tab_size": 2,
    "translate_tabs_to_spaces": true, 

 

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
