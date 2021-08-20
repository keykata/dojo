# macOS keyboard

The default macOS keyboard has so-called "dead keys". Some of these "dead keys"
interfere with GNU emacs/readline shortcuts that should be available by default
everywhere. To deal with this problem, I created a keyboard layout called
undead. I also created a `DefaultKeyBinding.dict` that provides many GNU
emacs/readline shortcuts.
To be honest, these steps are just for situation in which we cannot use Karabiner.


### Karabiner Combos in Finder

| Mode | Combo | Default | Action                                           |
| ---  | ---   | ---     | ---                                              |
| ⌘1   | ⌃b    | ←       | Go to directory/file on the left                 |
| ⌘1   | ⌃f    | →       | Go to directory/file on the right                |
| ⌘1   | ⌃n    | ↓       | Go to directory/file below                       |
| ⌘1   | ⌃p    | ↑       | Go to directory/file above                       |
| ⌘1   | ⌃⇧b   | ⇧←      | Extend selection to the left                     |
| ⌘1   | ⌃⇧f   | ⇧→      | Extend selection to the right                    |
| ⌘1   | ⌃⇧n   | ⇧↓      | Extend selection below                           |
| ⌘1   | ⌃⇧p   | ⇧↑      | Extend selection above                           |
| ⌘1   | ⌃⌘n   | ⌘↓      | Open directory/file                              |
| ⌘1   | ⌃⌘p   | ⌘↑      | Go to parent directory                           |
| ⌘1   | ⌥b    | ⌥←      | Go to directory/file on the left                 |
| ⌘1   | ⌥f    | ⌥l      | Go to directory/file on the right                |
| ⌘2   | ⌃b    | ←       | Fold directory                                   |
| ⌘2   | ⌃f    | →       | Unfold directory                                 |
| ⌘2   | ⌃n    | ↓       | Next directory/file                              |
| ⌘2   | ⌃p    | ↑       | Previous directory/file                          |
| ⌘2   | ⌃⇧n   | ⇧↓      | Select next directory/file                       |
| ⌘2   | ⌃⇧p   | ⇧↑      | Select previous directory/file                   |
| ⌘2   | ⌃⌘n   | ⌘↓      | Open directory/file                              |
| ⌘2   | ⌃⌘p   | ⌘↑      | Go to parent directory                           |
| ⌘2   | ⌃⌥n   | ⌥↓      | Go to bottom directory/file                      |
| ⌘2   | ⌃⌥p   | ⌥↑      | Go to top directory/file                         |
| ⌘2   | ⌃⌥⇧n  | ⌥⇧↓     | Extend selection to the bottom directory/file    |
| ⌘2   | ⌃⌥⇧p  | ⌥⇧↑     | Extend selection to the top directory/file       |
| ⌘3   | ⌃b    | ←       | Go to directories/files on the left              |
| ⌘3   | ⌃f    | →       | Go to directories/files on the right             |
| ⌘3   | ⌃n    | ↓       | Go to directory/file below                       |
| ⌘3   | ⌃p    | ↑       | Go to directory/file above                       |
| ⌘3   | ⌃⌘n   | ⌘↓      | Set directory to be leftmost                     |
| ⌘3   | ⌃⌘p   | ⌘↑      | Go to top-level directory (Macintosh HD)         |
| ⌘3   | ⌃⌥n   | ⌥↓      | Go to bottom directory/file                      |
| ⌘3   | ⌃⌥p   | ⌥↑      | Go to top directory/file                         |
| ⌘3   | ⌃⌥⇧n  | ⌥⇧↓     | Extend selection to the bottom directory/file    |
| ⌘3   | ⌃⌥⇧p  | ⌥⇧↑     | Extend selection to the top directory/file       |
| ⌘3   | ⌥b    | ⌥←      | Go to directories/files on the left              |
| ⌘3   | ⌥f    | ⌥→      | Go to directories/files on the right             |
| ⌘4   | ⌃b    | ←       | Go to directories/files on the left              |
| ⌘4   | ⌃f    | →       | Go to directories/files on the right             |
| ⌘4   | ⌃⇧b   | ⇧←      | Extend selection to the left                     |
| ⌘4   | ⌃⇧f   | ⇧→      | Extend selection to the right                    |
| ⌘4   | ⌃⌘n   | ⌘↓      | Open directory/file                              |
| ⌘4   | ⌃⌘p   | ⌘↑      | Go to parent directory                           |
| ⌘4   | ⌃⌥b   | ⌥←      | Go to leftmost directory/file                    |
| ⌘4   | ⌃⌥f   | ⌥→      | Go to rightmost directory/file                   |
| ⌘4   | ⌃⌥⇧b  | ⌥⇧←     | Extend selection to the leftmost directory/file  |
| ⌘4   | ⌃⌥⇧f  | ⌥⇧→     | Extend selection to the rightmost directory/file |
| ⌘4   | ⌥b    | ⌥←      | Go to directories/files on the left              |
| ⌘4   | ⌥f    | ⌥→      | Go to directories/files on the right             |

### Karabiner Combos in TextEdit

| Combo | Equivalent | Action        |
| ---   | ---        | ---           |
| ⌃n    | ↓          | Next line     |
| ⌃p    | ↑          | Previous line |
| ⌃⌘n   | ⌘↓         | Go to bottom  |
| ⌃⌘p   | ⌘↑         | Go to top     |
