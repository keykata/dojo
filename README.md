![keykata gif](https://raw.githubusercontent.com/keykata/dojo/main/images/ctrl-a_ctrl-d_ctrl-e_ctrl-h.gif)

# KeyKata
Train your fingers to
- Avoid repetitive stress injury
- Boost your productivity
- Conquer your keyboard

## Frequently Asked Questions (FAQ)

### What skills can I learn and practice here?
1. Computer Programming
2. Git Version Control

### What keyboard shortcuts are covered?
1. [GNU Emacs](https://www.gnu.org/software/emacs/manual/html_node/emacs/Key-Index.html#Key-Index)
2. [GNU Readline](https://www.gnu.org/software/bash/manual/html_node/Function-Index.html)
3. [Vim](http://vimdoc.sourceforge.net/)

### Where can I use and practice these shortcuts?
1. Terminal: MacOS, Linux, and Windows Subsystem for Linux (WSL)
2. Web browser: Firefox or any Chromium-based browser (e.g. Chrome, Edge)
3. Code editor: PyCharm, RStudio, or VSCode
4. Python or R console: IPython, ptpython, or radian
5. Jupyter notebook: JupyterLab or classic notebook interface

### How can I find out if KeyKata is right for me?
Basic information regarding KeyKata is in [Welcome to KeyKata](00_welcome_to_keykata.md).
To get a idea of what KeyKata is like, try the following three kata in the [GNU series](#gnu-series):
1. [Move to start and end of current line with ctrl a and ctrl e](gnu/01_ctrl-a-and-ctrl-e.md)
2. [Move left and right with ctrl b and ctrl f](gnu/03_ctrl-b-and-ctrl-f.md)
3. [Delete left and right with ctrl h, ctrl d, and ctrl w](gnu/07_ctrl-d_ctrl-h_ctrl-w_ctrl-delete.md)

### Where should I start?
- Complete the [GNU series](#gnu-series) to learn Emacs and Readline keybindings
- Complete the [Vim series](#vim-series) to
  - set up and practice Emacs and Readline keybindings in Vim insert mode
  - learn Vim normal and visual mode keybindings
- Complete the Web series to learn to use the [Vimium](#vimium) and [Surfingkeys](#surfingkeys) browser extensions

### What will I need?

You can complete most of the GNU series with
  - A UNIX terminal via
    - MacOS,
    - Linux, or
    - Windows Subsystem for Linux (WSL)
  - A code editor, like [RStudio](#rstudio), with Emacs mode enabled
  - GNU Emacs (terminal or GUI)

## Index

<details>
<summary>
Click the black triangle to toggle the Index
</summary>

- Command (or Cmd) ⌘
- Shift ⇧
- Option (or Alt) ⌥
- Control (or Ctrl) ⌃
- Escape ⎋
- Tab ⇥
- Return ↩
- Space ␣
- Left ←
- Down ↓
- Up ↑
- Right →
0. [Mac series](#mac-series)
  - [Alfred](#alfred)
  - [AltTab](#alttab)
  - [Rectangle](#Rectangle)
  - [Anaconda](#anaconda)
  - [CopyQ](#copyq)
  - [Jetbrains IDEs](#jetbrains-ides)
  - [Karabiner](#karabiner)
  - [RStudio](#rstudio)
  - [VimR](#vimr)
  - [Vimac](#vimac)
  - [Vimari](#vimari)
1. [GNU series](#gnu-series)
2. [Vim series](#vim-series)
3. [Web series](#web-series)
4. [Browser keybindings](#browser-keybindings)
  - [Vimium](#vimium)
  - [Surfingkeys keymap](#surfingkeys)
5. [Ctrl ⌃ keybindings](#ctrl-keybindings)
  - [Ctrl ⌃ setup](#ctrl-setup)
  - [Ctrl ⌃ keymap](#ctrl-keymap)
6. [Alt ⌥ keybindings](#alt-keybindings)
  - [Alt ⌥ setup](#alt-setup)
  - [Alt ⌥ keymap](#alt-keymap)
7. [Cmd ⌘ keybindings](#alt-keybindings)
  - [Cmd ⌘ setup](#cmd-setup)
  - [Cmd ⌘ keymap](#cmd-keymap)
8. [Command Line Tools](#command-line-tools)
  - [asciinema](#asciinema)
  - [ffmpeg](#ffmpeg)
  - [tmux](#tmux)
  - [miniconda](#miniconda)

</details>

## Mac series

Here are some of my favorite 3rd party MacOS applications (I'm planning a video for each one!):

### [Vimari](mac/000_mac_vimari.md)

- Install Vimari using App Store
- Practice scrolling (j / k and d / u)
- Practice using hints (f)
- Mention options for other browsers (Vimium & Surfingkeys)

### [Vimac](mac/001_mac_vimac.md)

- Install Vimac from vimacapp.com
- Grant permissions (Accessibility and Input Monitoring)
- Set shortcuts to toggle the menu bar (similar to Dock toggling shortcut)
- Access Vimac preferences using custom menu bar shortcut (⌘ ⌥ ;)
- Set Response Delay (0.15)
- Set key sequences and shortcuts
- Practice activating modes
- Practice scrolling (j / k and d / u)
- Practice using hint mode
- Mention options for Windows and Linux (e.g. hunt-n-peck)

### [Karabiner](mac/003_mac_vimac.md)
- Install brew
- Install Karabiner-Elements via brew
- Access Karabiner-Elements preferences using custom menu bar shortcut (⌘ ⌥ ;)
- Set up Caps Lock and Enter to work as Control when held
- Add Emacs and Bash style shortcuts

### [CopyQ](mac/003_mac_vimac.md)
- Install brew (if not already installed)
- Install CopyQ via brew
- Set up shortcuts

### Alfred
- Alternative to Spotlight Search

### AltTab
- Alternative to MacOS App Switcher and Window Alternator

### Rectangle
- Window manager

### VimR
- Vim GUI

### Cheatsheet
- View shortcuts for a given MacOS App

### CustomShortcuts
- Edit shortcuts for a given MacOS App

<details>
<summary>
Click the black triangle to toggle the Karabiner keyboard customization table
</summary>


| Before      | After                                                              | Import name                                                                                  | Rule name                                                          |
| ----------- | ------------------------------------------------------------------ | ------------------------------------------------------------------                           | ------------------------------------------------------------------ |
| `Caps Lock` | `Ctrl` when pressed with other keys, `Escape` when pressed  alone  | [Change caps_lock key (rev 4)](https://ke-complex-modifications.pqrs.org/#caps_lock)         | `Ctrl` when pressed with other keys, `Escape` when pressed  alone  |
| `Enter`     | `Ctrl` when pressed with other keys, `Enter` when pressed alone    | [Change return to control](https://ke-complex-modifications.pqrs.org/#return_to_ctrl)        | `Ctrl` when pressed with other keys, `Enter` when pressed alone    |
| `Ctrl d`    | `Delete_Forward`                                                   | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl h`    | `Delete_or_Backspace`                                              | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl i`    | `Tab`                                                              | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl [`    | `Escape`                                                           | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl m`    | `Return_or_Enter`                                                  | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl b`    | `Left_Arrow`                                                       | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl f`    | `Right_Arrow`                                                      | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl n`    | `Down_Arrow`                                                       | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl p`    | `Up_Arrow`                                                         | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl v`    | `Page_Down`                                                        | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl a`    | `Home` or `Cmd Left_Arrow`                                         | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl e`    | `End` or `Cmd Right_Arrow`                                         | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl w`    | `Alt Delete_or_Backspace`                                          | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Bash style Emacs key bindings (rev 2)                              |
| `Ctrl u`    | `Cmd Shift Left_Arrow, Delete_or_Backspace`                        | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Bash style Emacs key bindings (rev 2)                              |
| `Alt v`     | `Page_Up`                                                          | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Alt b`     | `Alt Left_Arrow`                                                   | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Alt f`     | `Alt Right_Arrow`                                                  | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Alt d`     | `Alt Delete_Forward`                                               | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |

</details>

[Back to index](#index)


## GNU series

<details>
<summary>
Click the black triangle to see the GNU series
</summary>

| Keybindings                                                                                                              | Description                                                                 |
| -----------                                                                                                              | ------------                                                                |
| [`ctrl a`, `ctrl e`](gnu/101_gnu_ctrl-a_ctrl-e.md)                                                                       | Move to line start/end                                                      |
| [`alt a`, `alt e`](gnu/102_gnu_alt-a_alt-e.md)                                                                           | Move to sentence start/end                                                  |
| [`ctrl b`, `ctrl f`](gnu/103_gnu_ctrl-b_ctrl-f.md)                                                                       | Move left/right                                                             |
| [`alt b`, `alt f`](gnu/104_gnu_alt-b_alt-f.md)                                                                           | Move word start/end                                                         |
| [`ctrl c`, `ctrl l`, `ctrl u`](gnu/105_gnu_ctrl-c_ctrl-l_ctrl-u.md)                                                      | Cancel, redraw screen, delete to line start                                 |
| [`alt c`, `alt l`, `alt u`](gnu/106_gnu_alt-c_alt-l_alt-u.md)                                                            | Capitalize, lowercase, uppercase word                                       |
| [`ctrl d`, `ctrl delete`, `ctrl h`, `ctrl w`, `ctrl space`](gnu/107_gnu_ctrl-d_ctrl-h_ctrl-w_ctrl-delete_ctrl-space.md)  | Delete left/left/right/word start, set mark                                 |
| [`alt d`, `alt delete`, `alt h`, `alt w`, `alt space`](gnu/108_gnu_alt-d_alt-h_alt-w_alt-delete_alt-space.md)            | Delete word end/start, kill/save region, delete whitespace                  |
| [`ctrl g`, `ctrl r`, `ctrl s`](gnu/109_gnu_ctrl-g_ctrl-r_ctrl-s.md)                                                      | Cancel, reverse search, search                                              |
| [`alt g`, `alt r`, `alt s`](gnu/110_gnu_alt-g_alt-r_alt-s.md)                                                            | Move prefix, revert line or top/middle/bottom, search prefix                |
| [`ctrl i`, `ctrl n`, `ctrl p`](gnu/111_gnu_ctrl-i_ctrl-n_ctrl-p.md)                                                      | Indent/complete, next, previous down                                        |
| [`alt i`, `alt n`, `alt p`](gnu/112_gnu_alt-i_alt-n_alt-p.md)                                                            | Indent, none, none                                                          |
| [`ctrl j`, `ctrl m`, `ctrl o`](gnu/113_gnu_ctrl-j_ctrl-m_ctrl-o.md)                                                      | Accept/new line, accept/new line, accept/new line                           |
| [`alt j`, `alt m`, `alt o`](gnu/114_gnu_alt-j_alt-m_alt-o.md)                                                            | Accept/new line, back to indentation, format prefix                         |
| [`ctrl k`, `ctrl y`, `ctrl dash`, `ctrl backslash`](gnu/115_gnu_ctrl-k_ctrl-y_ctrl-dash_ctrl-backslash.md)               | Kill to line end, paste from kill ring, undo, undo                          |
| [`alt k`, `alt y`, `alt dash`, `alt backslash`](gnu/116_gnu_alt-k_alt-y_alt-dash_alt-backslash.md)                       | Kill to sentence end, rotate kill ring, pass negative argument, expand word |
| [`ctrl q`, `ctrl v`](gnu/117_gnu_ctrl-q_ctrl-v.md)                                                                       | Literal insert, literal insert or page down                                 |
| [`alt q`, `alt v`](gnu/118_gnu_alt-q_alt-v.md)                                                                           | Realign text, page up                                                       |
| [`ctrl t`, `ctrl x`, `ctrl z`](gnu/119_gnu_ctrl-t_ctrl-x_ctrl-z.md)                                                      | Transpose characters, prefix, suspend                                       |
| [`alt t`, `alt x`, `alt z`](gnu/120_gnu_alt-t_alt-x_alt-z.md)                                                            | Transpose words, run command by name, zap to character                      |

</details>

## Vim series

<details>
<summary>
Click the black triangle to see the Vim series
</summary>

| Mode   | Keybindings                                                                                                                    | Description                                                                                                       |
| ------ | -----------                                                                                                                    | ------------                                                                                                      |
| Insert | [`ctrl a`, `ctrl e`](vim/201_vim-insert_ctrl-a_ctrl-e.md)                                                                      | Move to line start/end                                                                                            |
| Insert | [`alt a`, `alt e`](vim/202_vim-insert_alt-a_alt-e.md)                                                                          | Move to sentence start/end                                                                                        |
| Insert | [`ctrl b`, `ctrl f`](vim/203_vim-insert_ctrl-b_ctrl-f.md)                                                                      | Move left/right                                                                                                   |
| Insert | [`alt b`, `alt f`](vim/204_vim-insert_alt-b_alt-f.md)                                                                          | Move word start/end                                                                                               |
| Insert | [`ctrl c`, `ctrl l`, `ctrl u`](vim/205_vim-insert_ctrl-c_ctrl-l_ctrl-u.md)                                                     | Cancel, redraw screen, delete to line start                                                                       |
| Insert | [`alt c`, `alt l`, `alt u`](vim/206_vim-insert_alt-c_alt-l_alt-u.md)                                                           | Capitalize, lowercase, uppercase word                                                                             |
| Insert | [`ctrl d`, `ctrl delete`, `ctrl h`, `ctrl w`, `ctrl space`](vim/207_vim-insert_ctrl-d_ctrl-h_ctrl-w_ctrl-delete_ctrl-space.md) | Delete left/left/right/word start, set mark                                                                       |
| Insert | [`alt d`, `alt delete`, `alt h`, `alt w`, `alt space`](vim/208_vim-insert_alt-d_alt-h_alt-w_alt-delete_alt-space.md)           | Delete word end/start and kill/save region, delete whitespace                                                     |
| Insert | [`ctrl g`, `ctrl r`, `ctrl s`](vim/209_vim-insert_ctrl-g_ctrl-r_ctrl-s.md)                                                     | Cancel, reverse search, search                                                                                    |
| Insert | [`alt g`, `alt r`, `alt s`](vim/210_vim-insert_alt-g_alt-r_alt-s.md)                                                           | Move prefix, revert line or top/m-insertiddle/bottom, search prefix                                               |
| Insert | [`ctrl i`, `ctrl n`, `ctrl p`](vim/211_vim-insert_ctrl-i_ctrl-n_ctrl-p.md)                                                     | Indent/complete, next, previous down                                                                              |
| Insert | [`alt i`, `alt n`, `alt p`](vim/212_vim-insert_alt-i_alt-n_alt-p.md)                                                           | Indent, none, none                                                                                                |
| Insert | [`ctrl j`, `ctrl m`, `ctrl o`](vim/213_vim-insert_ctrl-j_ctrl-m_ctrl-o.md)                                                     | Accept/new line, accept/new line, accept/new line                                                                 |
| Insert | [`alt j`, `alt m`, `alt o`](vim/214_vim-insert_alt-j_alt-m_alt-o.md)                                                           | Accept/new line, back to indentation, format prefix                                                               |
| Insert | [`ctrl k`, `ctrl y`, `ctrl dash`, `ctrl backslash`](vim/215_vim-insert_ctrl-k_ctrl-y_ctrl-dash_ctrl-backslash.md)              | Kill to line end, paste from kill ring, undo, undo                                                                |
| Insert | [`alt k`, `alt y`, `alt dash`, `alt backslash`](vim/216_vim-insert_alt-k_alt-y_alt-dash_alt-backslash.md)                      | Kill to sentence end, rotate kill ring, pass negative argument, expand word                                       |
| Insert | [`ctrl q`, `ctrl v`](vim/217_vim-insert_ctrl-q_ctrl-v_.md)                                                                     | Literal insert, literal insert or page down                                                                       |
| Insert | [`alt q`, `alt v`](vim/218_vim-insert_alt-q_alt-v_.md)                                                                         | Realign text, page up                                                                                             |
| Insert | [`ctrl t`, `ctrl x`, `ctrl z`](vim/219_vim-insert_ctrl-t_ctrl-x_ctrl-z.md)                                                     | Transpose characters, prefix, suspend                                                                             |
| Insert | [`alt t`, `alt x`, `alt z`](vim/220_vim-insert_alt-t_alt-x_alt-z.md)                                                           | Transpose words, run command by name, zap to character                                                            |
| Normal | [`a`, `i`, `A`, `I`, `gi`](vim/221_vim-normal_a_i.md)                                                                          | Append/insert at cursor, Append/insert at line end/start, enter insert mode at last insert point                  |
| Normal | [`b`, `e`, `w`, `B`, `E`, `W`, `ge`, `gE`, `gw`](vim/222_vim-normal_b_e_w.md)                                                  | Move word by word, Move WORD by WORD                                                                              |
| Normal | [`c`, `d`, `C`, `D`, `gc`, `gd`](vim/223_vim-normal_c_d.md)                                                                    | Delete and enter insert mode or remain in normal mode                                                             |
| Normal | [`f`, `t`, `F`, `T`, `gf`, `gt`, `;`, `,`, `g;`, `g,`](vim/224_vim-normal_f_t_semicolon_comma.md)                              | Move on top of/next to a character                                                                                |
| Normal | [`gg`, `G`](vim/225_vim-normal_gg.md)                                                                                          | Move to the top/bottom of a file                                                                                  |
| Normal | [`h`, `j`, `k`, `l`, `H`, `J`, `L`, `gj`, `gk`](vim/226_vim-normal_h_j_k_l.md)                                                 | Move left/down/up/right, screen top/bottom                                                                        |
| Normal | [`m`, `M`, `gm`, `gM`, <kbq>`</kbd>, `'`](vim/227_vim-normal_m_backtick_single-quote.md)                                       | Set mark, move to screen/text middle, move to mark                                                                |
| Normal | [`n`, `N`, `/`, `?`, `gn`](vim/228_vim-normal_n_slash_question-mark.md)                                                        | Move to next/previous search match, search forward/backward                                                       |
| Normal | [`o`, `O`, `] space`, `[ space`](vim/229_vim-normal_o_square-bracket-space.md)                                                 | Add newline below/above and enter insert mode or stay in normal mode the top/bottom of a file or last/next change |
| Normal | [`p`, `P`, `gp`, `gP`](vim/230_vim-normal_p.md)                                                                                | Paste after/before cursor                                                                                         |


</details>

## Web series

TODO

## Browser keybindings

These browser keybindings will work for everyone who uses Firefox or a Chromium-based browser (e.g. Chrome, Edge).
For Safari, I recommend [Vimari](https://github.com/televator-apps/vimari#vimari).

Before starting to work through the keymaps for [Vimium](#vimium-keymap) and [Surfingkeys](#surfingkeys-keymap),
you need to
1. [install Vimium](https://github.com/philc/vimium#vimium---the-hackers-browser)
2. [install Surfingkeys](https://github.com/brookhong/Surfingkeys#surfingkeys---expand-your-browser-with-javascript-and-keyboard)

If don't want to install any browser extensions, you can at least get scrolling via [Vimac](#vimac) (MacOS only!).

### Vimium

<details>
<summary>
Click the black triangle to toggle the Vimium keymap table
</summary>

| Keybinding      | Action and link to lesson                        |
| -----------     | --------------------------------------           |
| `j` or `Ctrl e` | Scroll down                                      |
| `k` or `Ctrl y` | Scroll up                                        |
| `gg`            | Scroll to the top of the page                    |
| `G`             | Scroll to the bottom of the page                 |
| `d`             | Scroll a half page down                          |
| `u`             | Scroll a half page up                            |
| `h`             | Scroll left                                      |
| `l`             | Scroll right                                     |
| `zH`            | Scroll all the way to the left                   |
| `zL`            | Scroll all the way to the right                  |
| `r`             | Reload the page                                  |
| `yy`            | Copy the current URL to the clipboard            |
| `p`             | Open the clipboard's URL in the current tab      |
| `P`             | Open the clipboard's URL in a new tab            |
| `gu`            | Go up the URL hierarchy                          |
| `gU`            | Go to root of current URL hierarchy              |
| `i`             | Enter insert mode                                |
| `v`             | Enter visual mode                                |
| `V`             | Enter visual line mode                           |
| `gi`            | Focus the first text input on the page           |
| `f`             | Open a link in the current tab                   |
| `F`             | Open a link in a new tab                         |
| `Alt f`         | Open multiple links in a new tab                 |
| `yf`            | Copy a link URL to the clipboard                 |
| `[[`            | Follow the link labeled previous or <            |
| `]]`            | Follow the link labeled next or >                |
| `gf`            | Select the next frame on the page                |
| `gF`            | Select the page's main/top frame                 |
| `m`             | Create a new mark                                |
| `Backtick`      | Go to a mark                                     |
| `o`             | Open URL, bookmark or history entry              |
| `O`             | Open URL, bookmark or history entry in a new tab |
| `b`             | Open a bookmark                                  |
| `B`             | Open a bookmark in a new tab                     |
| `T`             | Search through your open tabs                    |
| `ge`            | Edit the current URL                             |
| `gE`            | Edit the current URL and open in a new tab       |
| `/`             | Enter find mode                                  |
| `n`             | Cycle forward to the next find match             |
| `N`             | Cycle backward to the previous find match        |
| `H`             | Go back in history                               |
| `L`             | Go forward in history                            |
| `t`             | Create new tab                                   |
| `J` or `gT`     | Go one tab left                                  |
| `K` or `gt`     | Go one tab right                                 |
| `^`             | Go to previously-visited tab                     |

| `g0`            | Go to the first tab                              |
| `g$`            | Go to the last tab                               |
| `yt`            | Duplicate current tab                            |
| `Alt p`         | Pin or unpin current tab                         |
| `Alt m`         | Mute or unmute current tab                       |
| `x`             | Close current tab                                |
| `X`             | Restore closed tab                               |
| `W`             | Move tab to new window                           |
| `<<`            | Move tab to the left                             |
| `>>`            | Move tab to the right                            |
| `?`             | Show help                                        |
| `gs`            | View page source                                 |

</details>

[Back to index](#index)

### Surfingkeys

<details>
<summary>
Click the black triangle to toggle the Surfingkeys keymap table
</summary>

| Keybinding     | Action and link to lesson                                                |
| -----------    | --------------------------------------                                  |
| `Alt s`        | Toggle SurfingKeys on current site                                      |
| `;ql`          | Show last action                                                        |
| `.`            | Repeat last action                                                      |
| `?`            | Show default keybindings                                                |
| `Alt i, Enter` | PassThrough mode to temporarily suppress SurfingKeys                    |
| `p`            | enter ephemeral PassThrough mode to temporarily suppress SurfingKeys    |
| `cf`           | Open multiple links in a new tab                                        |
| `gf`           | Open a link in non-active new tab                                       |
| `gi`           | Go to the first edit box                                                |
| `f`            | Open a link via hints                                                   |
| `Shift`        | Flip overlapped hints                                                   |
| `Space`        | Hide hints while space is pressed                                       |
| `;fs`          | Display hints to focus scrollable elements                              |
| `;m`           | Mouse out last element                                                  |
| `;di`          | Download image                                                          |
| `af`           | Open a link in active new tab                                           |
| `C`            | Open a link in non-active new tab                                       |
| `Ctrl h`       | Mouse over elements.                                                    |
| `Ctrl j`       | Mouse out elements.                                                     |
| `i`            | Go to edit box                                                          |
| `I`            | Go to edit box with vim editor                                          |
| `O`            | Open detected links from text                                           |
| `q`            | Click on an Image or a button                                           |
| `[[`           | Click on the previous link on current page                              |
| `]]`           | Click on the next link on current page                                  |
| `0`            | Scroll all the way to the left                                          |
| `cS`           | Reset scroll target                                                     |
| `cs`           | Change scroll target                                                    |
| `e`            | Scroll half page up                                                     |
| `d`            | Scroll half page down                                                   |
| `gg`           | Scroll to the top of the page                                           |
| `G`            | Scroll to the bottom of the page                                        |
| `j`            | Scroll down                                                             |
| `k`            | Scroll up                                                               |
| `h`            | Scroll left                                                             |
| `l`            | Scroll right                                                            |
| `$`            | Scroll all the way to the right                                         |
| `%`            | Scroll to percentage of current page                                    |
| `;w`           | Focus top window                                                        |
| `u`            | Scroll half page up                                                     |
| `w`            | Switch frames                                                           |
| `yt`           | Duplicate current tab                                                   |
| `yT`           | Duplicate current tab in background                                     |
| `g0`           | Go to the first tab                                                     |
| `g$`           | Go to the last tab                                                      |
| `gx0`          | Close all tabs on left                                                  |
| `gxt`          | Close tab on left                                                       |
| `gxT`          | Close tab on right                                                      |
| `gx$`          | Close all tabs on right                                                 |
| `gxx`          | Close all tabs except current one                                       |
| `gt`           | Choose a tab                                                            |
| `E`            | Go one tab left                                                         |
| `R`            | Go one tab right                                                        |
| `zr`           | zoom reset                                                              |
| `zi`           | zoom in                                                                 |
| `zo`           | zoom out                                                                |
| `T`            | Choose a tab                                                            |
| `Alt p`        | pin/unpin current tab                                                   |
| `Alt m`        | mute/unmute current tab                                                 |
| `on`           | Open newtab                                                             |
| `x`            | Close current tab                                                       |
| `X`            | Restore closed tab                                                      |
| `W`            | New window with current tab                                             |
| `<<`           | Move current tab to left                                                |
| `>>`           | Move current tab to right                                               |
| `gT`           | Go to first activated tab                                               |
| `gu`           | Go up one path in the URL                                               |
| `g?`           | Reload current page without query string(all parts after question mark) |
| `g#`           | Reload current page without hash fragment                               |
| `gU`           | Go to root of current URL hierarchy                                     |
| `;u`           | Edit current URL with vim editor, and open in new tab                   |
| `;U`           | Edit current URL with vim editor, and reload                            |
| `B`            | Go one tab history back                                                 |
| `F`            | Go one tab history forward                                              |
| `Ctrl 6`       | Go to last used tab                                                     |
| `S`            | Go back in history                                                      |
| `D`            | Go forward in history                                                   |
| `r`            | Reload the page                                                         |
| `ZZ`           | Save session and quit                                                   |
| `ZR`           | Restore last session                                                    |
| `sg`           | Search selected with google                                             |
| `sd`           | Search selected with duckduckgo                                         |
| `sb`           | Search selected with baidu                                              |
| `se`           | Search selected with wikipedia                                          |
| `sw`           | Search selected with bing                                               |
| `ss`           | Search selected with stackoverflow                                      |
| `sh`           | Search selected with github                                             |
| `sy`           | Search selected with youtube                                            |
| `yG`           | Capture current full page                                               |
| `yS`           | Capture scrolling element                                               |
| `ya`           | Copy a link URL to the clipboard                                        |
| `yma`          | Copy multiple link URLs to the clipboard                                |
| `ymc`          | Copy multiple columns of a table                                        |
| `ymv`          | Yank text of multiple elements                                          |
| `yc`           | Copy a column of a table                                                |
| `yq`           | Copy pre text                                                           |
| `yv`           | Yank text of an element                                                 |
| `yi`           | Yank text of an input                                                   |
| `ys`           | Copy current page's source                                              |
| `yj`           | Copy current settings                                                   |
| `yd`           | Copy current downloading URL                                            |
| `yy`           | Copy current page's URL                                                 |
| `yh`           | Copy current page's host                                                |
| `yl`           | Copy current page's title                                               |
| `yQ`           | Copy all query history of OmniQuery.                                    |
| `yf`           | Copy form data in JSON on current page                                  |
| `yg`           | Capture current page                                                    |
| `yp`           | Copy form data for POST on current page                                 |
| `cq`           | Query word with Hints                                                   |
| `cc`           | Open selected link or link from clipboard                               |
| `;pj`          | Restore settings data from clipboard                                    |
| `;pf`          | Fill form with data from yf                                             |
| `;pp`          | Paste html on current page                                              |
| `go`           | Open a URL in current tab                                               |
| `ab`           | Bookmark current page to selected folder                                |
| `t`            | Open a URL                                                              |
| `oi`           | Open incognito window                                                   |
| `ox`           | Open recently closed URL                                                |
| `oh`           | Open URL from history                                                   |
| `om`           | Open URL from vim-like marks                                            |
| `ob`           | Open Search with alias b                                                |
| `og`           | Open Search with alias g                                                |
| `od`           | Open Search with alias d                                                |
| `ow`           | Open Search with alias w                                                |
| `oy`           | Open Search with alias y                                                |
| `H`            | Open opened URL in current tab                                          |
| `Q`            | Open omnibar for word translation                                       |
| `b`            | Open a bookmark                                                         |
| `:`            | Open commands                                                           |
| `Ctrl d`       | Delete focused item from bookmark or history                            |
| `Ctrl i`       | Edit selected URL with vim editor, then open                            |
| `Ctrl j`       | Toggle Omnibar's position                                               |
| `Ctrl .`       | Show results of next page                                               |
| `Ctrl ,`       | Show results of previous page                                           |
| `Ctrl c`       | Copy all listed items                                                   |
| `Ctrl D`       | Delete all listed items from bookmark or history                        |
| `Ctrl r`       | Re-sort history by visitCount or lastVisitTime                          |
| `Esc`          | Close Omnibar                                                           |
| `Ctrl m`       | Create vim-like mark for selected item                                  |
| `Tab`          | Forward cycle through the candidates.                                   |
| `Shift Tab>`   | Backward cycle through the candidates.                                  |
| `Ctrl '>`      | Toggle quotes in an input element                                       |
| `Down_Arrow`   | Forward cycle through the candidates.                                   |
| `Up_Arrow`     | Backward cycle through the candidates.                                  |
| `Ctrl n`       | Forward cycle through the candidates.                                   |
| `Ctrl p`       | Backward cycle through the candidates.                                  |
| `v`            | Toggle visual mode                                                      |
| `/`            | Find in current page                                                    |
| `n`            | Next found text                                                         |
| `N`            | Previous found text                                                     |
| `zv`           | Enter visual mode, and select whole element                             |
| `V`            | Restore visual mode                                                     |
| `*`            | Find selected text in current page                                      |
| `0`            | backward lineboundary                                                   |
| `l`            | forward character                                                       |
| `h`            | backward character                                                      |
| `j`            | forward line                                                            |
| `k`            | backward line                                                           |
| `w`            | forward word                                                            |
| `e`            | forward word                                                            |
| `b`            | backward word                                                           |
| `)`            | forward sentence                                                        |
| `(`            | backward sentence                                                       |
| `}`            | forward paragraphboundary                                               |
| `{`            | backward paragraphboundary                                              |
| `$`            | forward lineboundary                                                    |
| `G`            | forward documentboundary                                                |
| `gg`           | backward documentboundary                                               |
| `gr`           | Read selected text                                                      |
| `o`            | Go to Other end of highlighted text                                     |
| `Enter`        | Click on node under cursor.                                             |
| `Shift Enter`  | Click on node under cursor.                                             |
| `zz`           | make cursor at center of window.                                        |
| `f`            | Forward to next char in visual mode                                     |
| `F`            | Backward to next char in visual mode                                    |
| `;`            | Repeat latest f, F in visual mode                                       |
| `,`            | Repeat latest f, F in opposite direction in visual mode                 |
| `p`            | Expand selection to parent element                                      |
| `q`            | Translate word under cursor                                             |
| `V`            | Select a word(w) or line(l) or sentence(s) or paragraph(p)              |
| `Ctrl u`       | Backward 20 lines                                                       |
| `Ctrl d`       | Forward 20 lines                                                        |
| `t`            | Translate selected text with google                                     |
| `m`            | Add current URL to vim-like marks                                       |
| `'`            | Jump to vim-like mark                                                   |
| `Ctrl '`       | Jump to vim-like mark in new tab.                                       |
| `;pm`          | Preview markdown                                                        |
| `;e`           | Edit Settings                                                           |
| `Ctrl Alt d`   | Mermaid diagram generator                                               |
| `ga`           | Open Chrome About                                                       |
| `gb`           | Open Chrome Bookmarks                                                   |
| `gc`           | Open Chrome Cache                                                       |
| `gd`           | Open Chrome Downloads                                                   |
| `gh`           | Open Chrome History                                                     |
| `gk`           | Open Chrome Cookies                                                     |
| `ge`           | Open Chrome Extensions                                                  |
| `gn`           | Open Chrome net-internals                                               |
| `gs`           | View page source                                                        |
| `;i`           | Open Chrome Inspect                                                     |
| `;j`           | Close Downloads Shelf                                                   |
| `cp`           | Toggle proxy for current site                                           |
| `;cp`          | Copy proxy info                                                         |
| `;ap`          | Apply proxy info from clipboard                                         |
| `;pa`          | set proxy mode `always`                                                 |
| `;pb`          | set proxy mode `byhost`                                                 |
| `;pd`          | set proxy mode `direct`                                                 |
| `;ps`          | set proxy mode `system`                                                 |
| `;pc`          | set proxy mode `clear`                                                  |
| `gr`           | Read selected text or text from clipboard                               |
| `;s`           | Toggle PDF viewer from SurfingKeys                                      |
| `;dh`          | Delete history older than 30 days                                       |
| `;db`          | Remove bookmark for current page                                        |
| `;t`           | Translate selected text with google                                     |
| `Ctrl y`       | Show me the money                                                       |
| `Ctrl e`       | Move the cursor to the end of the line                                  |
| `Ctrl f`       | Move the cursor to the beginning of the line                            |
| `Ctrl u`       | Delete all entered characters before the cursor                         |
| `Alt b`        | Move the cursor Backward 1 word                                         |
| `Alt f`        | Move the cursor Forward 1 word                                          |
| `Alt w`        | Delete a word backwards                                                 |
| `Alt d`        | Delete a word forwards                                                  |
| `Esc`          | Exit insert mode                                                        |
| `:`            | Input emoji in insert mode                                              |
| `Ctrl '`       | Toggle quotes in an input element                                       |
| `Ctrl i`       | Open vim editor for current input                                       |

</details>

[Back to index](#index)

## Ctrl keybindings

Ctrl ⌃ is used in the default keybindings of MacOS, Shell, Emacs, and Vim.
This section contains the most useful keybindings for editing text and working on the command line.

### Ctrl setup

Before starting this section,
I highly recommend
1. [installing Karabiner (MacOS only!)](https://github.com/keykata/setup/blob/main/karabiner-setup.md) and
2. setting up the Ctrl keyboard customizations below.
These keyboard customizations are absolutely life-changing and I honestly can't live without them!

<details>
<summary>
Click the black triangle to toggle the Ctrl ⌃ keyboard customizations table
</summary>

| Before      | After                                                              | Import name and link                                                                         | Rule name                                                          |
| ----------- | ------------------------------------------------------------------ | ------------------------------------------------------------------                           | ------------------------------------------------------------------ |
| `Caps Lock` | `Ctrl` when pressed with other keys, `Escape` when pressed  alone  | [Change caps_lock key (rev 4)](https://ke-complex-modifications.pqrs.org/#caps_lock)         | `Ctrl` when pressed with other keys, `Escape` when pressed  alone  |
| `Enter`     | `Ctrl` when pressed with other keys, `Enter` when pressed alone    | [Change return to control](https://ke-complex-modifications.pqrs.org/#return_to_ctrl)        | `Ctrl` when pressed with other keys, `Enter` when pressed alone    |
| `Ctrl d`    | `Delete_Forward`                                                   | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl h`    | `Delete_or_Backspace`                                              | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl i`    | `Tab`                                                              | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl [`    | `Escape`                                                           | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl m`    | `Return_or_Enter`                                                  | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl b`    | `Left_Arrow`                                                       | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl f`    | `Right_Arrow`                                                      | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Meta f`    | `Option Right_Arrow`                                               | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Meta b`    | `Option Left_Arrow`                                                | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Meta d`    | `Option Delete_Forward`                                            | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Ctrl n`    | `Down_Arrow`                                                       | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl p`    | `Up_Arrow`                                                         | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl v`    | `Page_Down`                                                        | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl a`    | `Home` or `Cmd Left_Arrow`                                         | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl e`    | `End` or `Cmd Right_Arrow`                                         | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [control+keys] (rev 10)                         |
| `Ctrl w`    | `Option Delete_or_Backspace`                                       | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Bash style Emacs key bindings (rev 2)                              |
| `Ctrl u`    | `Cmd Shift Left_Arrow, Delete_or_Backspace`                        | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Bash style Emacs key bindings (rev 2)                              |

</details>

[Back to index](#index)

## Ctrl Keymap

Interestingly, `Ctrl y` seems to work in Finder, TextEdit, and Chrome, but not Safari or Firefox.

<details>
<summary>
Click the black triangle to toggle the Ctrl ⌃ keymap table
</summary>

| Keybinding   | Action and link to lesson                                 | Emacs              | Shell              | MacOS              | Vim                |
| -----------  | --------------------------------------                    | ------             | ------             | ------             | ----               |
| `Ctrl a`     | [Move to start of current line](gnu/01_ctrl-a_ctrl-e.md)  | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl b`     | [Move left one character](gnu/02_ctrl-b_ctrl-f.md)        | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl c`     | Cancel                                                    | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl d`     | [Delete right one character](gnu/05_ctrl-h_ctrl-d.md)     | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl e`     | [Move to end of current line](gnu/01_ctrl-a_ctrl-e.md)    | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl f`     | [Move right one character](gnu/03_ctrl-b_ctrl-f.md)       | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl g`     | Cancel                                                    | :white_check_mark: | :white_check_mark: | :x:                | :x:                |
| `Ctrl h`     | [Delete left](gnu/05_ctrl-h_ctrl-d.md)                    | :x:                | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| `Ctrl i`     | Indent                                                    | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl j`     | Newline / Confirm                                         | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl k`     | Kill to line end                                          | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| `Ctrl l`     | Clear screen                                              | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl m`     | Newline / Confirm                                         | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl n`     | Down / Next                                               | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl o`     | Newline / Confirm                                         | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl p`     | Down / Previous                                           | :white_check_mark: | :white_check_mark: | :white_check_mark: | :white_check_mark: |
| `Ctrl q`     | Insert literally                                          | :x:                | :x:                | :x:                | :white_check_mark: |
| `Ctrl r`     | Reverse Search                                            | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl s`     | Vimac Scroll mode<sup>[1](#forward-search)</sup>          | :white_check_mark: | :x:                | :x:                | :x:                |
| `Ctrl t`     | Transpose characters                                      | :white_check_mark: | :white_check_mark: | :white_check_mark: | :x:                |
| `Ctrl u`     | Kill to line start                                        | :x:                | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl v`     | Insert literally<sup>[2](#page-down)</sup>                | :x:                | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl w`     | Kill previous word                                        | :white_check_mark: | :x:                | :x:                | :x:                |
| `Ctrl x`     | Prefix for chord bindings                                 | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl y`     | Yank / paste from killring                                | :white_check_mark: | :white_check_mark: | :x:                | :x:                |
| `Ctrl z`     | Put process in background                                 | :white_check_mark: | :white_check_mark: | :x:                | :white_check_mark: |
| `Ctrl /`     | Undo                                                      | :white_check_mark: | :white_check_mark: | :x:                | :x:                |
| `Ctrl _`     | Undo                                                      | :white_check_mark: | :white_check_mark: | :x:                | :x:                |
| `Ctrl \`     | Toggle input method                                       | :white_check_mark: | :x:                | :x:                | :x:                |
| `Ctrl ]`     | Find next character<sup>[3](#cancel-recursive-edit)</sup> | :white_check_mark: | :x:                | :x:                | :x:                |
| `Ctrl Space` | Vimac hint mode<sup>[4](#set-mark)</sup>                  | :x:                | :x:                | :x:                | :x:                |

</details>

[Back to index](#index)

#### Alternative Ctrl ⌃ shortcuts:

<details>
<summary>
Click the black triangle to toggle the Alternative Ctrl ⌃ shortcuts table
</summary>

| Keybinding   | Action                                                      | From   |
| -----------  | --------------------------------------                      | ------ |
| `Ctrl s`     | <a name="forward-search">1</a>. Forward Search        | Emacs  |
| `Ctrl v`     | <a name="page-down">2</a>. Page down             | Emacs  |
| `Ctrl ]`     | <a name="cancel-recursive-edit">3</a>. Cancel recursive edit | Emacs  |
| `Ctrl Space` | <a name="set-mark">4</a>. Set mark              | Emacs  |
| `Ctrl Space` | insert previously inserted text and exit insert mode        | Vim    |
| `Ctrl a`     | insert previously inserted text                             | Vim    |
| `Ctrl e`     | insert character below                                      | Vim    |
| `Ctrl y`     | insert character above                                      | Vim    |

</details>

[Back to index](#index)

## Alt keybindings

Alt ⌥ is synonymous with Option and Meta.
Please don't @ me.

### Alt setup

Before starting this section,

I recommend starting by
1. [installing Karabiner (MacOS only!)](https://github.com/keykata/setup/blob/main/karabiner-setup.md) and
2. setting up the Alt keyboard customizations below.

<details>
<summary>
Click the black triangle to toggle the Alt ⌥ keyboard customizations table
</summary>

| Before      | After                | Import name and link                                                                                  | Rule name                                                          |
| ----------- | -------------------- | ------------------------------------------------------------------                           | ------------------------------------------------------------------ |
| `Alt v`     | `Page_Up`            | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Alt b`     | `Alt Left_Arrow`     | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Alt f`     | `Alt Right_Arrow`    | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |
| `Alt d`     | `Alt Delete_Forward` | [Emacs key bindings (rev 12)](https://ke-complex-modifications.pqrs.org/#emacs_key_bindings) | Emacs key bindings [option+keys] (rev 5)                           |

</details>

[Back to index](#index)

### Alt Keymap

- [Vim does not use Alt at all](https://vim.fandom.com/wiki/Unused_keys)
- [MacOS uses Alt only in combination with other modifiers](https://support.apple.com/en-us/HT201236)
- [Readline uses Alt alone and in combination with Ctrl](https://www.gnu.org/software/bash/manual/html_node/Function-Index.html)

<details>
<summary>
Click the black triangle to toggle the Alt ⌥ keymap table
</summary>

| Keybinding     | Action and link to lesson                                 | Emacs              | Shell              | MacOS  | Vim    |
| ------------   | -----------------------------------------                 | ------             | ------             | ------ | ------ |
| `Alt a`        | Move to previous sentence / code block                    | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt b`        | Move to previous word start                               | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt c`        | Capitalize current/next character                         | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt d`        | Kill next word                                            | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt e`        | Move to next sentence / code block                        | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt f`        | Move to next word start                                   | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt g`        | Prefix for chord bindings                                 | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt h`        | Select current/next paragragh                             | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt i`        | Indent to next indentation level                          | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt j`        | Newline and match indent / comment                        | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt k`        | Delete to end of current sentence                         | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt l`        | Lowercase word and move to word end                       | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt m`        | Move to first non-whitespace character                    | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt n`        | None                                                      | :x:                | :x:                | :x:    | :x:    |
| `Alt o`        | Prefix for chord bindings                                 | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt p`        | None                                                      | :x:                | :x:                | :x:    | :x:    |
| `Alt q`        | Align current paragragh                                   | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt r`        | Undo all changes to line<sup>[1](#move-to-top-btm)</sup>  | :x:                | :white_check_mark: | :x:    | :x:    |
| `Alt t`        | Transpose words                                           | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt u`        | Uppercase word and move to word end                       | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt v`        | Scroll page down                                          | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt w`        | Save to killring                                          | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt x`        | Prefix for chord bindings                                 | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt y`        | Cycle killed text from killring                           | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt z`        | Kill up to provided character                             | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt /`        | Complete filename<sup>[2](#delete-whitespace)</sup>       | :x:                | :white_check_mark: | :x:    | :x:    |
| `Alt Bar`      | Pass selected region to shell command                     | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt ?`        | Find references                                           | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt .`        | Insert previous argument<sup>[3](#find-definitions)</sup> | :x:                | :white_check_mark: | :x:    | :x:    |
| `Alt ,`        | Pop back to where `Alt .` was last invoked                | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt =`        | Count number of words in region                           | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt -`        | Begin negative argument for next command                  | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt '`        | Begin Emacs abbrev                                        | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt ;`        | Run Emacs comment command                                 | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt :`        | Run Emacs eval-expression command                         | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt {`        | Move to start of paragragh                                | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt }`        | Move to end of paragragh                                  | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt ~`        | Mark file as not needing to be saved                      | :white_check_mark: | :x:                | :x:    | :x:    |
| `Alt Backtick` | AltTab Alternate window<sup>[4](#show-menu-bar)</sup>     | :x:                | :x:                | :x:    | :x:    |
| `Alt !`        | Complete command<sup>[5](#run-shell-command)</sup>        | :x:                | :white_check_mark: | :x:    | :x:    |
| `Alt <`        | Beginning of history                                      | :x:                | :white_check_mark: | :x:    | :x:    |
| `Alt >`        | End of history                                            | :x:                | :white_check_mark: | :x:    | :x:    |
| `Alt 1`        | Pass 1 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 2`        | Pass 2 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 3`        | Pass 3 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 4`        | Pass 4 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 5`        | Pass 5 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 6`        | Pass 6 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 7`        | Pass 7 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 8`        | Pass 8 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt 9`        | Pass 9 as numeric argument to next command                | :white_check_mark: | :white_check_mark: | :x:    | :x:    |
| `Alt Space`    | Alfred search<sup>[6](#leave-only-one-space)</sup>        | :x:                | :x:                | :x:    | :x:    |

</details>

[Back to index](#index)

#### Alternative Alt shortcuts:

<details>
<summary>
Click the black triangle to toggle the Alternative Alt shortcuts table
</summary>

| Keybinding     | Action                                                                                    | From   |
| -----------    | --------------------------------------                                                    | ------ |
| `Alt r`        | <a name="move-to-top-btm">1</a>. Move to window top/bottom                                | Emacs  |
| `Alt /`        | <a name="delete-whitespace">2</a>. Delete all whitespace around cursor                    | Emacs  |
| `Alt .`        | <a name="find-definitions">3</a>. Find definitions                                        | Emacs  |
| `Alt Backtick` | <a name="show-menu-bar">4</a>. Show menu bar                                              | Emacs  |
| `Alt !`        | <a name="run-shell-command">5</a>. Run shell command                                      | Emacs  |
| `Alt Space`    | <a name="leave-only-one-space">6</a>. Replace all whitespace around cursor with one space | Emacs  |

</details>

[Back to index](#index)

## Cmd keybindings

### Cmd in the terminal

The Cmd ⌘ key is not used in Shell, Emacs, or Vim default bindings.
It is possible to use Cmd ⌘ in the terminal by editing iTerm escape codes.
With modified escapes shown below, Cmd ⌘ will send Alt ⌥ when combined with Enter ↩.

<details>
<summary>
Click the black triangle to toggle the Cmd ⌘ in the terminal table
</summary>

| Keybinding             | Escape Code  |
| -----------            | ------------ |
| `Shift Enter`          | ^[[13u;2u    |
| `Cmd Enter`            | ^[[13u;3u    |
| `Cmd Shift Enter`      | ^[[13u;4u    |
| `Ctrl Enter`           | ^[[13u;5u    |
| `Ctrl Shift Enter`     | ^[[13u;6u    |
| `Cmd Ctrl Enter`       | ^[[13u;7u    |
| `Cmd Ctrl Shift Enter` | ^[[13u;8u    |

</details>

[Back to index](#index)

<details>
<summary>
Click the black triangle to toggle the Cmd ⌘ keymap table
</summary>


| Keybinding  | Action and link to lesson                                                 | MacOS              | 3rd party application  |
| ----------- | ------------------------------------------------------------------------ | ------------------ | ---------------------- |
| `Cmd a`     | Select all                                                               | :white_check_mark: | :x:                    |
| `Cmd b`     | Toggle bold text                                                         | :white_check_mark: | :x:                    |
| `Cmd c`     | Copy selection                                                           | :white_check_mark: | :x:                    |
| `Cmd d`     | Duplicate selected file or Select the Desktop when Opening or Saving     | :white_check_mark: | :x:                    |
| `Cmd e`     | Eject the selected volume of disk                                        | :white_check_mark: | :x:                    |
| `Cmd f`     | Search for text in a document or start Spotlight search in Finder        | :white_check_mark: | :x:                    |
| `Cmd g`     | Find the next occurrence of previously found item                        | :white_check_mark: | :x:                    |
| `Cmd h`     | Hide all windows of currently focuses app                                | :white_check_mark: | :x:                    |
| `Cmd i`     | Get info for current file or toggle italics text                         | :white_check_mark: | :x:                    |
| `Cmd j`     | Show View options                                                        | :white_check_mark: | :x:                    |
| `Cmd k`     | Open the Connect to Server window                                        | :white_check_mark: | :x:                    |
| `Cmd l`     | None                                                                     | :x:                | :x:                    |

</details>

[Back to index](#index)

## Command Line Tools

### asciinema
Play `.cast` files

### ffmpeg
Play audio files (`.mp3`, `.aac`, or `.ogg`)

### tmux
Run scripts that split the terminal into windows

### miniconda
Install command line tools along with Python and R

#### Linux or Windows Keyboard setup:
If you
- are using Linux or Windows but prefer MacOS, try [Kinto](https://github.com/rbreaves/kinto#kintosh).
- prefer Windows, try [Keyboard Manager](https://github.com/microsoft/PowerToys/wiki/Keyboard-Manager), which is included with [Windows 10 PowerToys](https://github.com/microsoft/PowerToys#about).
- prefer Linux, try [xcape](https://github.com/alols/xcape#xcape) or [Key Mapper](https://github.com/sezanzeb/key-mapper#key-mapper).

[Back to index](#index)
