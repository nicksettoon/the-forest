# vscode

1. learn markdown
    1. <https://www.markdowntutorial.com/lesson/2/>
2. install Vim extension
3. alskdjf
4. Move lines around screen with alt+hjkl
5. Add lines to settings.json to allow for easy sentence navigation
    "vim.normalModeKeyBindings": [
        {
            "before": ["S-n"],
            "after": ["("]
        },
        {
            "before": ["n"],
            "after": [")"]
        }
    ],
6. navigate selections width j and k
    selectNextSuggestion
    selectPreviousSuggestion
7. inserting line above/below with vim "o" adds number to list or bullet point
8. create, check, and uncheck markdown todo item with hotkey
9. preview markdown ctrl+shift+alt+p
10. Headings ctrl+tab
    markdown.extension.editing.toggleHeadingUp
    markdown.extension.editing.toggleHeadingDown
11. markdown create table of contents

Ctrl+P will let you navigate to any file or symbol by typing its name
Ctrl+Tab will cycle you through the last set of files opened
Ctrl+Shift+P will bring you directly to the editor commands
Ctrl+Shift+O will let you navigate to a specific symbol in a file
Ctrl+G will let you navigate to a specific line in a file

navigate command panel with j and k
regenerate markdown links
    ctrl+shift+alt+l
toggle todo list items
    markdown.extension.checkTaskList
    ctrl+alt+c
collapse and expanding indented sections
    jump to parent indention (or top of the current indented section)
    collapse current indented section
markdown links not working when indented?
navigate explorer menu sections (workspace, timeline, terminal, backlinks, etc...) with hjkl
