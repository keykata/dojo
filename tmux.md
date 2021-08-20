| Key   | Action                                            | Default      | Vim analog                            | Mnemonic          |
| ---   | ------                                            | -------      | ---------------                       | ---               |
| +     | resize-pane -U 10                                 | CTRL-<Up>    | CTRL-W_+                              | <Ctrl-w>+ in Vim  |
| -     | resize-pane -D 10                                 | CTRL-<Down>  | CTRL-W_-                              | <Ctrl-w>- in Vim  |
| 0     | select-window -t:^                                | None         | :tabl :tablast                        | 0 in Vim          |
| 9     | select-window -t:$                                | None         | :tabl :tablast                        | Cmd-9 in MacOS    |
| <     | resize-pane -L 10                                 | CTRL-<Left>  | CTRL-W_<                              | <Ctrl-w>< in Vim  |
| =     | select-layout -E                                  | None         | CTRL-W_=                              | Equal             |
| >     | resize-pane -R 10                                 | CTRL-<Right> | CTRL-W_>                              | <Ctrl-w>> in Vim  |
| C     | select-pane -t :.- \; resize-pane -Z              | None         | CTRL-W_c :clo :close                  | Close             |
| Enter | display-panes                                     | q            | None                                  | Enter pane number |
| N     | previous-window                                   | p            | :tabp :tabprevious gT :tabN           | :tabN in Vim      |
| Q     | kill-pane                                         | None         | CTRL-W_q CTRL-W_CTRL-Q                | Quit              |
| R     | rotate-window -U                                  | None         | CTRL-W_r CTRL-W_CTRL-R                | Rotate            |
| T     | break-pane                                        | !            | CTRL-W_T                              | Tab               |
| W     | select-pane -t :.-                                | None         | CTRL-W_W                              | Window            |
| X     | swap-pane -U                                      | {            | CTRL-W_x CTRL-W_CTRL-X                | eXchange          |
| a     | choose-session                                    | s            | None                                  | All sessions      |
| b     | select-pane -t:.-1                                | None         | CTRL-W_b CTRL-W_CTRL-B                | Bottom-left       |
| c     | select-pane -t :.+ \; resize-pane -Z              | None         | CTRL-W_c :clo :close                  | Close             |
| d     | detach-client                                     | d            | None                                  | Detach            |
| e     | select-layout -E                                  | None         | CTRL-W_=                              | Equal/Even        |
| f     | command-prompt "find-window '%%'"                 | f            | :b :bu :buf :buffer                   | Find              |
| g     | display-message                                   | i            | CTRL-G :f :fi :file                   | Ctrl-g in Vim     |
| h     | select-pane -L                                    | <Left>       | CTRL-W_<Left> CTRL-W_CTRL-H CTRL-W_h  | h in Vim          |
| i     | last-window                                       | l            | g<Tab> CTRL-W_g<Tab> <C-Tab>          | g_CTRL-I in Vim   |
| j     | select-pane -D                                    | <Down>       | CTRL-W_<Down> CTRL-W_CTRL-J CTRL-W_j  | j in Vim          |
| k     | select-pane -U                                    | <Up>         | CTRL-W_<Up> CTRL-W_CTRL-K CTRL-W_k    | k in Vim          |
| l     | select-pane -R                                    | <Right>      | CTRL-W_<Right> CTRL-W_CTRL-L CTRL-W_l | l in Vim          |
| m     | select-pane -m                                    | m            | m :ma :mark :k                        | Mark              |
| n     | next-window                                       | n            | :tabn :tabnext gt                     | Next              |
| o     | resize-pane -Z                                    | z            | CTRL-W_o CTRL-W_CTRL-O :on :only      | Only One          |
| p     | last-pane                                         | p            | CTRL-W_p CTRL-W_CTRL-P                | Previous Pane     |
| q     | confirm-before -p "Kill pane #P? (y/n)" kill-pane | x            | CTRL-W_q CTRL-W_CTRL-Q                | Quit              |
| r     | rotate-window                                     | CTRL-O       | CTRL-W_R                              | Rotate            |
| s     | split-window -v                                   | "            | CTRL-W_s CTRL-W_CTRL-S :sp :split     | Split             |
| t     | select-pane -t:.1                                 | None         | CTRL-W_t CTRL-W_CTRL-T                | Top-left          |
| u     | choose-tree                                       | None         | None                                  | Unfold            |
| v     | split-window -h                                   | %            | CTRL-W_v CTRL-W_CTRL-V :vs :vsplit    | Vertical          |
| w     | select-pane -t :.+                                | o            | CTRL-W_w CTRL-W_CTRL-W                | Window            |
| x     | swap-pane -D                                      | }            | CTRL-W_x CTRL-W_CTRL-X                | eXchange          |
| y     | choose-buffer                                     | None         | None                                  | Yank              |
| z     | resize-pane -Z                                    | z            | CTRL-W_o CTRL-W_CTRL-O :on :only      | Zoom              |
