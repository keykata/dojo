# macOS keyboard

The default macOS keyboard has so-called "dead keys". Some of these "dead keys"
interfere with GNU emacs/readline shortcuts that should be available by default
everywhere. To deal with this problem, I created a keyboard layout called
undead. I also created a `DefaultKeyBinding.dict` that provides many GNU
emacs/readline shortcuts.
To be honest, these steps are just for situations in which we cannot use Karabiner.

Modifier key icons:
  ƒ: Function
  ⌃: Control
  ⌥: Option
  ⇧: Shift
  ⌘: Command

Finder modes:
  ⌘1: icons
  ⌘2: list
  ⌘3: columns
  ⌘4: gallery

### Karabiner Combos in Finder

| Combo | Default | Action (Mode)                                   |
| ---   | ---     | ---                                             |
| ƒ⌃b   | ƒ←      | Scroll to top (⌘1,⌘2,⌘3), Scroll to start (⌘4)  |
| ƒ⌃f   | ƒ→      | Scroll to bottom (⌘1,⌘2,⌘3), Scroll to end (⌘4) |
| ƒ⌃n   | ƒ↓      | Scroll down (⌘1,⌘2,⌘3)                          |
| ƒ⌃p   | ƒ↑      | Scroll up (⌘1,⌘2,⌘3)                            |
| ⌃b    | ←       | Go left (⌘1,⌘3,⌘4), Fold directory (⌘2)         |
| ⌃f    | →       | Go right (⌘1,⌘3,⌘4), Unfold directory (⌘2)      |
| ⌃n    | ↓       | Go down (⌘1,⌘2,⌘3,⌘4)                           |
| ⌃p    | ↑       | Go up (⌘1,⌘2,⌘3,⌘4)                             |
| ⌃⇧b   | ⇧←      | Select left (⌘1,⌘4)                             |
| ⌃⇧f   | ⇧→      | Select right (⌘1,⌘4)                            |
| ⌃⇧n   | ⇧↓      | Select below (⌘1,⌘2,⌘3,⌘4)                      |
| ⌃⇧p   | ⇧↑      | Select above (⌘1,⌘2,⌘3,⌘4)                      |
| ⌃⌘n   | ⌘↓      | Open directory/file (⌘1,⌘2,⌘3,⌘4)               |
| ⌃⌘p   | ⌘↑      | Go to parent directory (⌘1,⌘2,⌘3,⌘4)            |
| ⌃⌥b   | ⌥←      | Go to leftmost directory/file (⌘4)              |
| ⌃⌥f   | ⌥→      | Go to rightmost directory/file (⌘4)             |
| ⌃⌥n   | ⌥↓      | Go to bottom directory/file (⌘2,⌘3)             |
| ⌃⌥p   | ⌥↑      | Go to top directory/file (⌘2,⌘3)                |
| ⌃⌥⇧n  | ⌥⇧↓     | Select to bottom directory/file (⌘2,⌘3)         |
| ⌃⌥⇧p  | ⌥⇧↑     | Select to top directory/file (⌘2,⌘3)            |
| ⌥b    | ⌥←      | Go left (⌘1,⌘3,⌘4), Fold directory (⌘2)         |
| ⌥f    | ⌥→      | Go right (⌘1,⌘3,⌘4), Unfold directory (⌘2)      |


### Karabiner Combos in TextEdit

| Combo | Equivalent | Action        |
| ---   | ---        | ---           |
| ⌃n    | ↓          | Next line     |
| ⌃p    | ↑          | Previous line |
| ⌃⌘n   | ⌘↓         | Go to bottom  |
| ⌃⌘p   | ⌘↑         | Go to top     |
